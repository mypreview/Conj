# Conj Theme Child Theme

If you want to customize the theme at coding level, not just CSS, we would strongly suggest using a child theme for that. A child theme allows you to override the parent theme’s functions, template files and CSS so you will be able to adjust them as you want.

!> Here is the thing that causes the most confusion: **You don’t always need a child theme**.

* Edit the theme’s CSS stylesheet.
* Edit any of the theme’s PHP templates.
* Edit the theme’s `functions.php` file. Even just to add a single line of code.
* Modify any of the theme’s assets stored in the theme folder — including JavaScript files and images.

If you answered **Yes** to any of these questions, you definitely need a child theme.

## What Is a Child Theme?

A child theme is a theme that inherits the same functionality and styling of another theme, called the parent theme. By creating and working on a child theme, you can add, modify or disable parts of your site without changing the original files of the parent theme.

You don’t have to worry anymore about updates to the parent theme since there is no need to exclude your modified files from the updating process or to re-add your changes to fit the new version. After having the child theme installed on your website, you end up significantly speeding up your development time.

## Overriding Template Files

If you want to edit the code in the theme’s template files like `header.php`, `index.php`, etc, you can just copy the file from the parent theme and put it into your child theme folder then edit it from there.

## Overriding Functions

If you want to edit the functions of the parent theme, for example, the `conj_posted_on()` function, you can do that by copying only the function from the parent theme and put it into the ```functions.php``` file of your child theme.

?> Note that, you must copy only the `function() {...}` part, NOT including the `function_exists()` wrapper.

## Overriding Theme’s CSS

You can do this by either using the [Additional CSS](making-css-edits) field under the Customizer window or adding your custom CSS code into the `style.css` file of your child theme.

## Remember!

Whenever you finished updating the parent theme, make sure to check all the code you use in your child theme and update them as necessary to reflect any changes in the parent theme. You might back up your custom code first, update the files with the latest version, then apply your custom code back.

By doing this, it ensures that the files and code in your child theme are always up-to-date and to prevent any problem that might occur.

![Conj Theme Child Theme](img/conj-child-theme.png)

## Install Via WordPress

1. Log into your WordPress website and navigate to **Appearance** » **Themes**.
2. Once you are on the themes page, click on the **Add New** button at the top.
3. Click **Upload Theme**.
4. Choose ```conj-child.zip``` from your local computer or machine and hit **Install Now** button.<br/>
*You have to downloaded the whole package **All files & documentation** and extract it to locate the child theme file which is named `conj-child.zip`).*
5. Once WordPress has unpacked and installed the child theme, just click **Activate** to activate the Conj child theme.

## Install Via FTP<br/>*(File Transfer Protocol)*

To manually upload the [Conj - eCommerce WordPress Child Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview), login to your hosting (server) file manager with using FTP client credentials.

?> The theme or child theme files will be stored on your server in the ```wp-content/themes``` location.

1. Unzip **All files and documentation** (buyer files) you downloaded from [Envato](https://themeforest.net/) which will include the theme, child theme, documentation access, demo data and the licensing information.
2. Upload only the extracted folder `conj-child` to your server.
3. Log into your WordPress website and navigate to **Appearance** » **Themes**.
4. Locate the **Conj Child** *(child)* theme and click **Activate** to activate the Conj child theme.

## Additional Links

* [Child Themes](https://codex.wordpress.org/Child_Themes)
* [What is a Parent Theme?](https://developer.wordpress.org/themes/advanced-topics/child-themes/#what-is-a-parent-theme)
* [What is a Child Theme?](https://developer.wordpress.org/themes/advanced-topics/child-themes/#what-is-a-child-theme)
