
# Page Builder Quote 

It is an example of the custom content type for Page Builder Magento 2 based on adobe documentation.
This control works with Hyva Page Builder module. Using Tailwind on the frontend.

Before you use it you should upgrate your magento to 2.4.3, turn on Page Builder modules, install hyva and Page Builder for hyva.
https://gitlab.hyva.io/hyva-themes/magento2-page-builder

## How to use
Clone this repo to the root of your Magento instance. Navigate to the ```app/code/ ```directory and copy ```PageBuilder``` catalog from ```hyva-page-builder-playground```

copy the CSS sheet to your projects Hyvä based theme.

```
cp app/code/PageBuilder/Quote/view/frontend/web/css/page-builder-quote.css {PATH_TO_YOUR_THEME}/web/tailwind/components/page-builder-quote.css
```

Add CSS to your Tailwind CSS output
Edit the {PATH_TO_YOUR_THEME}/web/tailwind/tailwind-source.css file and import the above CSS file by adding 

```
@import url(components/page-builder-quote.css); 
```

before the line containing the 

```
/* purgecss end ignore */
```
