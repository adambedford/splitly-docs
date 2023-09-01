# Splitly Documentation

## Configuring DNS for your Site

Once you've created a site in Splitly, you'll need to connect it to the domain you specified. Typically, this is a subdomain. e.g. `get.mysite.com`.

Open up your domain provider's control panel and navigate to DNS. Create a CNAME record for the subdomain you'll be using with Splitly (in the example above, the subdomain is `get`) and point it to the value specified in your Splitly Site setup instructions. Save the record.

Please note, propagation can take up to 72 hours. Once complete, return to your Splitly Site page and click 'Validate' under 'Configure DNS'.

## Installing the Splitly Pixel

Click 'View Snippet' on your Splitly Site setup instructions and copy the code. Assuming you're using Shopify, navigate to your store > Settings > Customer Events > Add Custom Pixel. Enter the name 'Splitly'. Paste the code you previously copied from Splitly and click Save.
