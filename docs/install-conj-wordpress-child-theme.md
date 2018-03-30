# Install and activate child theme 

If you want to customize the theme at coding level, not just CSS, we would strongly suggest using a child theme for that. A child theme allows you to override the parent theme's functions, template files and CSS so you will be able to adjust them as you want.

![Conj child theme screenshot](img/screenshot-child-theme.png)

!> Here is the thing that causes the most confusion: **You don't always need a child theme**.

* Edit the theme's CSS stylesheet.
* Edit any of the theme's PHP templates.
* Edit the theme's ```functions.php``` file. Even just to add a single line of code.
* Modify any of the theme's assets stored in the theme folder — including javascript files and images.

If you answered **Yes** to any of these questions, you need a child theme.

<hr/>

## What is a child theme?

A Child Theme is a theme that inherits the same functionality and styling of another theme, called the parent theme. By creating and working on a child theme, you can add, modify or disable parts of your site without changing the original files of the parent theme.

You do not have to worry anymore about updates to the parent theme since there is no need to exclude your modified files from the updating process or to re-add your changes to fit the new version. After the creation of a Child Theme, you end up significantly speeding up your development time.

<hr/>

## Overriding template files

If you want to edit the code in the theme's template files like ```header.php```, ```index.php```, etc, you can just copy the file from the parent theme and put it into your child theme folder then edit it from there.

<hr/>

## Overriding functions

If you want to edit the functions of the parent theme, for example, the ```mypreview_conj_posted_on()``` function, you can do that by copying only the function from the parent theme and put it into the ```functions.php``` file of your child theme.

!> Note that, you must copy only the ```function() {...}``` part, NOT including the ```function_exists()``` wrapper.
