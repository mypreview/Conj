# Site Verification Tools


## Google Search Console

Follow the steps below to verify your WordPress site with Google Search Console:

1. First, You’ll need to sign in with a **Google account** if you’re not already logged in.
2. Navigate to [Google Search Console](https://www.google.com/webmasters/verification/home?hl=en) to get started.
3. Click on **Add a property**.
4. Enter your site address.
5. Click the **Continue** button.
6. Click on the **Alternate Methods** tab.
7. You’ll see a line of HTML code like the following:<br/>
   `<meta name="google-site-verification" content="jV5rz9P2s2wdDsnwTu4tD-gmruKUrqBGjs" />`
8. Copy the entire meta tag shown in the screen/field.
9. Leave the verification page open and go to your site dashboard *(in a new tab/window)*.
   1. Login to the your WordPress Dashboard
   2. Click the **Conj PowerPack** menu.
   3. From the sidebar on the left, select the **Site Verification** tab.
   4. Locate the **Google Search Console** text-field and paste your meta tag in.
   5. Click the **Save Changes** button.
9. Go back to Google’s verification page and click **Verify**.

### Google Warnings

In case you have received an email from Google with a subject of an alert in your **Webmaster Tools** dashboard that your site’s security certificate could not be found, this means your site was inadvertently added as a secure site. 

An example of the message you may have received:

```txt

Dear Webmaster,

The host name of your site, https://example.com, does not match any of the “Subject Names” in your SSL certificate [….]
This will cause many web browsers to block users from accessing your site, or to display a security warning message when your site is accessed.

To correct this problem, please get a new SSL certificate by a Certificate Authority (CA) with a “Subject Name” or “Subject Alternative DNS Names” that matches your host name.

```

If a message like the above arrived in your inbox, you'd need to remove the site from your Webmaster Tools account, and then add it back as a standard site.

1. Log in to [Google Webmaster Tools](https://www.google.com/webmasters/tools/) with your **Google account**.
2. Below the button for **Manage Site**, click **Delete Site**.
3. Click the button to **Add a Site** and follow the [instructions above](site-verification-tools?id=google-search-console).

## Bing Webmaster Center



## Pinterest Site Verification

## Yandex Site Verification
