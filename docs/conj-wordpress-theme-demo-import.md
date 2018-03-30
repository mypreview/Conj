# Importing dummy data 

Right after installing a fresh copy of Conj theme and [WooCommerce](https://wordpress.org/plugins/woocommerce/) plugin you may find you have an empty store. There are no products, orders, reviews, and more by default. This is because you can get started right away creating your own products and setting up WooCommerce exactly for the needs of your store.

!> We do **NOT** supply the exact images you see on our demo within the dummy data as the pictures of the site cannot be redistributed due to copyright restrictions and are for demo purposes only.

In addition to the above, it is NOT recommended to take next steps forward if you have existing content in your WordPress installation, as it will add numerous posts, pages, categories, media and more to your site.
Also, try to replace all content as soon as possible to avoid adverse SEO effects or image licensing repercussions.

## Built-in demo importer

Importing the demo data is the easiest way to setup your theme. It will allow you to edit everything instead of creating content from scratch super quickly and with ease.

!> Before you begin, make sure to deactivate all 3rd party plugins except the WooCommerce which is recommended by the theme.

![Built-in one click demo importer](img/demo-import.png)

* Install [One Click Demo Import](https://wordpress.org/plugins/one-click-demo-import) plugin.
* Navigate to **Appearance** » **Import Demo Data**.
* Click the **Import Demo Data** button and the plugin will now load all dummy content from the imported files.

<hr/>

## Manual demo import

In some cases, the automatic demo import doesn’t work correctly, and most likely this happens when the website is on a local server without an internet connection in this case you have to import demo content manually by following the steps below.


### Dummy content import

![Dummy content import](img/wordpress-importer.png)

* Navigate to **Tools** » **Import**.
* If you don’t have the [WordPress importer](https://wordpress.org/plugins/wordpress-importer/) installed, first install it by selecting **Install Now**.
* Once it’s installed select **Run Importer**.
* Choose **WordPress** from the list.
* Upload ```dummy-data/content.xml``` from the package you downloaded earlier then click on upload file and **Import** button.
* Check or uncheck the **Download and import file attachments** checkbox.<br/>*This will import all the sample product images to your site if checked.*
* Click **Submit** and the plugin will now load dummy content from the imported file.
