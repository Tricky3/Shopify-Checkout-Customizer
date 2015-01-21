# User-Configurable Shopify Checkout CSS
## Enhanced Responsive Checkout Settings

These files constitute a reset for and enhancement of the new Shopify Responsive Checkout styles, to provide configuration of fonts, colors and layout via Shopify's Theme Settings admin panel.

Before attempting the customizations below, ensure that you have [upgraded to Shopify's Responsive Checkout](http://docs.shopify.com/manual/configuration/store-customization/page-specific/checkout-page/how-to-upgrade-to-responsive-checkout)

### Unleashed Options

* Base Font Size : Insert a value that matches your shop's general configuration
* Border Style : Border Radius Border Radius values for inputs and buttons
* Desktop View: Max width Insert a value that matches your shop's general configuration 	
* Desktop View: Padding Value for the External Wrap configure the outermost padding value 	
* Wrap Background Color
* Center Header Elements : Choose between a center-aligned layout or a left-aligned one 	
* Different Background Colors for Header, Main and Footer Area 
* Header Padding 
* Header Margin
* Shop Name ( Company Logo ) Choose between uploading a custom Image or using plain text 	
* Shop Logo Image : max width
* Shop Name Text Color (In the case no image is used for the Shop Logo)
* Header background : Choose between using a custom image (repeating and seamless motif) or using a flat color as a background for the header area 	
* Custom Header Background Image 
* Header Background Color 
* Tagline Add an explanatory/prompt line on the header 	
* Tagline Color
* Tagline Font Size
* Headings Color
* Headings Text Transform 	
* Headings Padding
* h1 + h2 font Size 	
* h3 + h4 Font Size 	
* h5 + h6 Font Size
* Main Background Color
* Section Border Color : separating the distinct section between customer info, shipping and billing
* Label Color 	
* Placeholder Color
* Fieldset Background Color 	
* Fieldset Border Color
* Field Focus Color 	
* Field Padding
* Field Error : Background Color 	
* Field Error : Text Color
* Field Error : Label 	
* Field Error : Placeholder
* Order Summary : Background colorfill 	
* Order Summary : Text Color 	
* Order Summary : Border Color
* Price Color 	
* Price Font size
* Currency Color 	
* Currency Background Color Fill 	
* Currency Font Size
* Button Font Size 	
* Button Padding 	
* Button Text Transform
* Button Focus : Background Color 	
* Button Focus : Text Color
* Inset Checkout Buttons : Changes section, discount and gift card button
* Inset Buttons Font Size 	
* Inset Buttons Top Position 	
* Inset Buttons Padding
* Inset Buttons : Background Color 	
* Inset Buttons : Color
* Inset Buttons : Hover State Background Color 	
* Inset Buttons : Hover State Color
* Footer Text Transform 	
* Footer Link Separator : Add a symbol that you wish to be displayed in-between the footer's navigation links (e.g. "|") 	
* Footer Top-border Color
* Footer Font Size 	
* Footer Padding 	
* Footer Text Color
* Footer Background Color Fill 	
* Footer Wrap Background Color
* Footer Link Color
* Footer Link Hover Color
* Custom CSS area

### Usage

* Place contents of `assets` folder to your Shopify theme. `checkout.scss.liquid` will reset the native SCSS file that Shopify delivers. (This action will ONLY affect your checkout pages)
* Copy the new `fieldset` element and its contents within `config/settings.html` into your own `settings.html` file. (This action will substitute the default _Checkout_ tab)
</ol>

### Compatibility

Made to seamlessly integrate with [Tricky3eme](https://github.com/rickydazla/Tricky3eme) and will work on any other Shopify theme too. 