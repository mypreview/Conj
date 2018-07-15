# Enabling `WP_Debug` In WordPress

`WP_Debug` is a constant *(a permanent global variable)* that when enabled will display any PHP errors on the front-end of your site, and this is the most useful tool when troubleshooting your site for any potential errors or warnings. If disabled and your site has an error you may see a blank white screen or content missing on the site but no error message, that makes it nearly impossible to figure out what the problem exactly is.

Follow the steps below to enable `WP_Debug` for your WordPress installation.

## Enable `WP_Debug` Via Plugin

If you are looking for a one-click method or you are not comfortable editing a file using FTP access in general simply use this plugin to turn on `WP_DEBUG` mode instead.

1. Install and activate [SO Turn On Debug](https://wordpress.org/plugins/so-turn-on-debug/) plugin.

## Enable `WP_Debug` Via WordPress

1. Access your website’s root folder via **FTP** or **SFTP**.
2. Locate the `wp-config.php` file.
3. Open this file in any text editor.
4. Search for `WP_Debug` and if you find it set the value to `TRUE` if currently set to `FALSE`.
5. If you didn’t locate `WP_Debug` scroll down near the bottom of the file and add the following code right before the line that says `That's all, stop editing! Happy blogging.`.

!> The true and false values in the example are not set in apostrophes `(')` because they are boolean values.

## Additional Links

* [WP DEBUG](https://codex.wordpress.org/WP_DEBUG)
* [Debugging in WordPress](https://codex.wordpress.org/Debugging_in_WordPress)
