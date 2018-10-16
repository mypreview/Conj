# Creating A Google Maps API Key

As of June 22, 2016, Google requires an API key to display maps on a website. Acquiring an API key is free and allows up to 25,000 requests per day. You will not be billed unless usage goes over the [free number of views](https://cloud.google.com/maps-platform/).

?> If your shop requires more than 25000 requests per day, you will be responsible for extra charges. However, for 90% of website owners, this will not be needed.

Follow the steps below to obtain a Google Maps JavaScript API key:

1. First, You’ll need to sign in with a **Google account** if you’re not already logged in.
2. Navigate to [Google Developers Console](https://console.developers.google.com/flows/enableapi?apiid=maps_backend,static_maps_backend,geocoding_backend,maps_embed_backend,places_backend,geolocation,timezone_backend&keyType=CLIENT_SIDE&reusekey=true) to get started.
3. If you haven’t created a project in the Google Developers Console before, you will need to do that first.
   1. Choose the **Create a Project** option in the dropdown.
   2. Click the **Continue** button<br/>*You may need to agree to the terms before proceeding.*
4. On the screen to create the browser API key Use `CONJ THEME` for the key name to help identify it in the future.
5. Leave the referrers field empty for now to make testing easier.
6. You’ll also need to add the domain name of the site whereever you’re using the [Conj - eCommerce WordPress Child Theme](https://themeforest.net/item/conj-ecommerce-wordpress-theme/21935639?ref=mypreview).
   * We recommend adding more than one entry using the following patterns:
   * `*.yourdomain.com yourdomain.com`
   * To avoid problems with **www** and non-www versions of your domain, don’t include the www part of your website URL.
7. Click the **Create** button.
8. Copy the key shown in the screen/field to enter it in your WordPress admin panel so your site can access the Google Maps APIs.
   1. Login to the your WordPress Dashboard.
   2. Click the **Conj PowerPack** menu.
   3. From the sidebar on the left, select the **3rd Party API** tab.
   4. Locate the **Google Maps API** text-field and Paste your API key in.
   5. Click the **Save Changes** button.

?> If you didn’t copy your API key in the earlier step, you can find it on the [Credentials screen](https://console.developers.google.com/apis/credentials) in the Google Developers Console.
