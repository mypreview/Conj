# Increasing WordPress Memory Limit

By default, most of the small-budget shared hosting servers have a meager and limited amount of memory allocated to PHP which can cause a blank screen [(white screen of death)](conj-theme-installation-errors?id=white-screen-of-death) or other types of the errors on your site. 

By default, WordPress will attempt to increase memory allocated to PHP to **40MB** *(code is at the beginning of `/wp-includes/default-constants.php`)* for single site and **64MB** for multisite, so the setting in `wp-config.php` should reflect something higher than **40MB** or **64MB** depending on your setup.

## Increase PHP Memory to 64MB

```php
define( 'WP_MEMORY_LIMIT', '64M' );
```

## Increase PHP Memory to 96MB

```php
define( 'WP_MEMORY_LIMIT', '96M' );
```

## Additional Links

* [Increasing memory allocated to PHP](https://codex.wordpress.org/Editing_wp-config.php#Increasing_memory_allocated_to_PHP)
