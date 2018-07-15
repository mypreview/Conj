# Theme Installation Errors

The [Conj - eCommerce WordPress Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview) should install without any errors on any up to date WordPress installation, although on some occasions people may encounter issues which most common ones are outlined below:

## Missing the `style.css`

This is one of the common issues that may occur when installing a WordPress theme. The following error message may appear when uploading or activating the theme.

!> The package could not be installed. The theme is missing the `style.css` stylesheet.

In most cases, the reason to receive this error is if you have uploaded the incorrect file. This is because the package that you have [downloaded from ThemeForest](download-conj-wordpress-theme) usually includes additional files such as the documentation, dummy data, license, etc.

To solve this make sure you are uploading only the WordPress theme installable file which in this case is called `conj.zip`

## 500 Internal Server Errors

This error typically happens for one of the few reasons mentioned below:

* Your server’s PHP memory limit is too low.
* You are trying to upload the **All files and documentation** (buyer files) file and not just the installable WordPress theme.
* The upload limit on your server isn’t enough and you must update your `php.ini` file to increase it.

Contact your web hosting support team and they will be able to check the server logs and locate the root cause of the error.

?> This error is most likely to occur on a small-budget shared hosting server, so it’s important for you to begin researching other options so you can move your site to a server capable of handling your growing site.

## Didn’t Send Any Data<br/>*(`ERR_EMPTY_RESPONSE`)*

This error usually means that your server’s upload limit is small. To address this issue you need to contact your service provider support if you aren’t sure how to get your upload limit increased to at least **20MB**.

## White Screen Of Death

Both PHP errors and database errors can manifest as a white screen, a blank screen with no information, commonly known in the WordPress community as the WordPress White Screen of Death (WSOD).

The [WP_DEBUG feature](https://codex.wordpress.org/Editing_wp-config.php#Debug) often provides additional information. If you are still experiencing problems and are looking in your error logs you can check out the [PHP errors](https://codex.wordpress.org/User:Raggedrobins/Common_WordPress_Errors#PHP_Errors) for more information.

## Additional Links

* [Common WordPress Errors](https://codex.wordpress.org/Common_WordPress_Errors)
* [Increasing memory allocated to PHP](https://codex.wordpress.org/Editing_wp-config.php#Increasing_memory_allocated_to_PHP)
* [Theme is missing the `style.css` stylesheet error](https://help.market.envato.com/hc/en-us/articles/202821510-Theme-is-missing-the-style-css-stylesheet-error)
