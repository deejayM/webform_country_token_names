# webform_country_token_names
A way to override country codes in webform with a country name instead . 

This is for Drupal 7 - Webform and Webform Country List

I feel like this module shouldn't exist but should be dealt with by https://www.drupal.org/search/site/address%20field%20token

So if you know how to achieve this then let me know dj@flowmo.co

What I have is a country code selection in webform .  When outputting this in the Webform Emails the value in  [submission:values:country]  is the country code.  

I needed to output the Country name.

The code in this module is reliant on the fact the fieldname is 'country'  - if it isn't you'll either need to change the field name or customise this code.
