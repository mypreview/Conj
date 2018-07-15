# Translating With Poedit

The [Conj - eCommerce WordPress Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview) is translation-ready and localized using the GNU framework. It is the common way to translate WordPress core and almost any theme or plugin.

If you need more advanced features such as translating menu items, categories, etc. Feel free to visit [WPML](https://wpml.org/purchase/purchase-process/) website and find out more about their premium services and plugin.

If you don't have the [Poedit](https://poedit.net/) software installed on your local computer, go ahead and download Poedit now. When the download completes, go through the installation wizard to install it.

![Translating With Poedit](img/translating-with-poedit.png)

After you have installed Poedit, select **Create new translation** option in Poedit welcome screen and browse yours computer for a local copy of the **.pot** file for the theme. You should be able to find it in the folder named languages within the the theme folder.

You will be prompted with the option **Language of the translation**. Start typing the language and Poedit will fill it in for you. After you have entered the language, open a set of parentheses and enter the name of the country.

The resulting **.po** file will be named according to abbreviations for the language and associated country. In our case, we are using the English United Kingdom, so our file will be ```en_GB.po```.

!> Poedit creates **MO** and **PO** extensions automatically, but if you’re interested here’s a lengthy [list of country and language codes](http://www.fincher.org/Utilities/CountryLanguageList.shtml).

Go through every line of human-readable string in the [Conj - eCommerce WordPress Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview) and translate it to the selected language. As a reminder, the **.pot** file has already compiled everything you need to translate. That’s how those lines of text got there.

You need to select each line, one by one and enter the translation in the box on the bottom left corner of the Poedit interface.

When you are about to save your new translation file from Poedit, the software automatically generates a new **.mo** file and saves it in the same directory on your hard drive.

After saving the files on your hard disk, use any FTP client application to upload both files to the languages folder in the theme directory. Now all you have to do is notify WordPress to use your new translation files.

WordPress will automatically detect and use the right language files if they already exist.

## PO and MO Translation Files

WordPress uses **PO** and **MO** files to manage translations. In fact, WordPress only needs **MO** files to handle translations. **PO** files are human-readable; Those files contains a list of strings ready to be translated or with a translation already included.

**MO** files just compiled exports from the **PO** files and used by WordPress to get the conversion of each string to translate the theme. If you try to open a **MO** file with a regular text editor, you will not understand anything of its content.

## Files That Enable Translation

*.pot: This file is a portable object template that contains all of the text to be translated.
*.po: The portable object file contains the original text and the translations.
*.mo: This is the machine object file. When your translation is complete, you will convert or export your .po file to this file type so that WordPress can use it.

## Loading Translation Files

Translations can be filed in the ```/languages/``` directory.

!> The [Conj - eCommerce WordPress Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview) will look in this directory for translations as a fallback.

However, it is recommended that you use the global WordPress language directory and install your translations like so:

```php
/wp-content/languages/themes/conj-it_IT.mo
```

!> This way they will not be lost or overwritten during the [Conj - eCommerce WordPress Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview) updates.

Alternatively you can put translations in your child theme:

```php
/wp-content/themes/conj-child/languages/it_IT.mo
```

The theme first looks in the [WordPress Languages Directory](https://developer.wordpress.org/themes/functionality/localization/), and then in the language directory of your child theme.

## Share Your Language Files

In case you have already translated the [Conj - eCommerce WordPress Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview) a lot of users would be thrilled if you share your translation files with the community.

For translations, please send over translated language files directly to us at [support@](mailto:support@mypreview.one) email address; We will include the translation files within your name and credit to the next release, so other people who speak your language can use it.
