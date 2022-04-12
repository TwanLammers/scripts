# Data Layer push - Customer ID

Below you will find a script to add a Customer ID to the data layer, for the purpose of using it in Google Tag Manager.

You can add this code directly above the Google Tag Manager script that is directly placed in the <head> of the page.

```
<script>
dataLayer = dataLayer || [];
dataLayer.push({
 'visitorId': <number of the specific visitor>,
 'profileId': <number of profile that is logged in>,
 'audienceCode': <code of the audience>, // for example MP_DG01
 });
</script>
```
