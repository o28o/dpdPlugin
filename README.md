# dictPlugin

For those who want to click the word and get the translation of the prefered Online dictionary. It's made for Pali Language, but can be customized to any Language or any Online Dictionary that supports word lookup in the URL parameters like this: https://somedict.online/?word=dukkha (GET parameters)

## for End Users (requires installing browser extention and setup):
There is another way to add Pali Lookup for literally any site. [Read](https://github.com/o28o/dictPlugin/blob/main/ExtentionMethod.md) 

## for Webmasters (requires adding js and css to the site code): 
Simple yet very convenient Pali Lookup Dictionary for any site.

This example uses Digital Pali Dictionary as Pali Dictionary but you can modify the link and use any Dictionary of your choice. 
More information about DPD [here](https://github.com/digitalpalidictionary/dpd-db). 

## Demos
These demos might be slightly outdated. Please check the latest live version on [Dhamma.gift Read](https://dhamma.gift/sc/?q=sn56.11)

### [English Demo](https://o28o.github.io/plugin/index.html?s=pi$)

### [Russian Demo](https://o28o.github.io/plugin/demo-ru-ml.html?s=dukkh)

## Instructions

To make Pali text clickable:


1.  Clone repo 
2.  The Pali text should be marked with class="pli-lang" e.g. `<span class="pli-lang">Pali text</span>` or <p> or <div>.
   
3. Styles should be applied in the `<head>` section:
   ```html
   <link rel="stylesheet" href="assets/css/paliLookup.css">

4. JavaScript should be applied after the Pali text, e.g., at the end of the <body> section. You can modify connection url or desired endpoint in this file:
   ```html
   <script src="assets/js/paliLookup.js"></script>

