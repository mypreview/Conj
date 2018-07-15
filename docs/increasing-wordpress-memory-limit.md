# Increasing WordPress Memory Limit

By default, most of the small-budget shared hosting servers have a meager and limited amount of memory allocated to PHP which can cause a blank screen [(white screen of death)](conj-theme-installation-errors?id=white-screen-of-death) or other types of the errors on your site. 

By default, WordPress will attempt to increase memory allocated to PHP to **40MB** *(code is at the beginning of `/wp-includes/default-constants.php`)* for single site and **64MB** for multisite, so the setting in `wp-config.php` should reflect something higher than **40MB** or **64MB** depending on your setup.

## Edit `wp-config.php` File

To adjust on your own, follow the steps below:

1. Access your website’s root folder via **FTP** or **SFTP**.
2. Locate the `wp-config.php` file.
3. Open this file in any text editor.
4. Add one of the lines below to the top, before the line that says, `That's all, stop editing! Happy blogging.`:

### Increase PHP Memory to 64MB

```php
define( 'WP_MEMORY_LIMIT', '64M' );
```

### Increase PHP Memory to 96MB

```php
define( 'WP_MEMORY_LIMIT', '96M' );
```

### Increase PHP Memory to 256M<br/>*(Administration Tasks)*

Administration tasks require much memory than usual operation. When in the administration area, the memory can be increased or decreased from the ```WP_MEMORY_LIMIT``` by defining ```WP_MAX_MEMORY_LIMIT```.

```php
define( 'WP_MAX_MEMORY_LIMIT', '256M' );
```

## Edit `PHP.ini` File

If you have access to your `PHP.ini` file, change the line in the file that line shows **64M** try **256M**:

```txt
memory_limit = 256M ; Maximum amount of memory a script may consume (64MB)
```

## Edit `.htaccess` File

In case, you don’t have access to `PHP.ini` file try adding this to an `.htaccess` file instead:

```txt
php_value memory_limit 256M
```

## GoDaddy, Hostgator and 1&1 Users

On a very few hosts, like GoDaddy, Hostgator and 1&1 basic plan, you may encounter issues as demo content import failure, empty page content, Customizer settings not being saved, incomplete page rendering, etc which are caused by the fact that the basic plan of these service providers are NOT meet the minimum server requirements to work with a modern WordPress theme.

!> Note that many hosts set the PHP limit at **8MB**.

The modifications mentioned above may not work if your host does not allow for increasing the PHP memory limit. You may need to search your admin panel, or if you do not feel comfortable in trying the above methods, you need to talk to your hosting support and asking them to increase your memory limit.

## Additional Links

* [Increasing memory allocated to PHP](https://codex.wordpress.org/Editing_wp-config.php#Increasing_memory_allocated_to_PHP)
* [Increasing the WordPress Memory Limit](https://docs.woocommerce.com/document/increasing-the-wordpress-memory-limit/)
