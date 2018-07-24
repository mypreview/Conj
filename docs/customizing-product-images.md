# Customizing Product Images

Since [WooCommerce 3.3](https://woocommerce.wordpress.com/2017/12/09/wc-3-3-will-look-great-on-all-the-themes), users can now control the width and height of their main images, as well as the cropping with visual cues as to what the photos might look like on the frontend.

## Image Types

* **Catalog images** are medium-sized images that appear on the **Shop** page, **Category** pages, and for **Related products**, **Up-sells** and **Cross-sells**.
* **Product thumbnails** are the smallest images used in the **Cart**, **Widgets** and (optional) **Gallery images** underneath the **Single Product Image** on individual product details pages.
* **Single product image** is the largest image and refers to the main/featured image.<br/>*Product Images settings in WooCommerce Customizer do not apply to these.*

!> Note that product image settings in WooCommerce Customizer do not apply to single product image dimensions.

## Resize And Crop Thumbnail Images

![Updating WooCommerce product image sizes to a custom aspect ratio](img/resize-crop-product-images.png)

1. On the frontend, in the **Admin bar**, **Customize**.
2. On the backend, click **Appearance** » **Customize**.
3. Navigate to **WooCommerce** » **Product Images** section.
  - **1:1** — Images will be cropped into a square.
  - **Custom** — Images will be cropped to a custom aspect ratio.
  - **Uncropped** — Images will display using the aspect ratio in which they were uploaded.
  
!> If you are using **WooCommerce 3.3.X** or above 	__regenerating product thumbnails by__ installing and configuring any 3rd party plugin is no longer needed and all changes in product catalog or product image sizes triggers WooCommerce to auto-size and auto-update thumbnail and product catalog images for you.

## Fixing Blurry Product Images

When your product images are blurry two things could be happening:

* **One**, your image size settings, may not be adequate (too small) for theme. This can cause problems as the theme wants an image at ```418 x 418 pixels```, but you are giving it one at ```200 x 200 pixels```.
* **Two**, the original images you uploaded are not high-resolution enough. Even if your image settings are right, the original image source is too small. The only thing you can do in this case is re-upload appropriately sized images, to begin with.
