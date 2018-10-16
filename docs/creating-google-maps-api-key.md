# Creating A Google Maps API Key

As of June 22, 2016, Google requires an API key to display maps on a website. Acquiring an API key is free and allows up to 25,000 requests per day. You will not be billed unless usage goes over the [free number of views](https://cloud.google.com/maps-platform/).

Follow these steps to get an API key:

1. Navigate to [Google Developers Console](https://console.developers.google.com/flows/enableapi?apiid=maps_backend,static_maps_backend,geocoding_backend,maps_embed_backend,places_backend,geolocation,timezone_backend&keyType=CLIENT_SIDE&reusekey=true) to get started.<br/>*You may need to log in or create a Google account first.*
2. If you haven’t created a project in the Google Developers Console before, you will need to do that first.
   1. Choose the **Create a Project** option in the dropdown.
   2. Click the **Continue** button<br/>*You may need to agree to the terms before proceeding.*
3. On the screen to create the browser API key Use `CONJ THEME` for the key name to help identify it in the future.
4. Leave the referrers field empty for now to make testing easier.
5. Enter your domain name to prevent anyone else from using your key.
6. Click the **Create** button.
7. Copy the generated **API** key to enter it in your WordPress admin panel so your site can access the Google Maps APIs.
   1. Login to the your WordPress Dashboard.
   2. Click the **Conj PowerPack** menu.
   3. From the sidebar on the left, select the **3rd Party API** tab.
   4. Locate the **Google Maps API** text-field and Paste your API key in.
   5. Click the **Save Changes** button.

?> If you didn’t copy your API key in the earlier step, you can find it on the [Credentials screen](https://console.developers.google.com/apis/credentials) in the Google Developers Console.
