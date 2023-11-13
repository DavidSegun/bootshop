# David Shopify Theme
Shopify Starter Theme powered by Bootstrap framework (v5), developed respecting [Shopify themes requirements](https://shopify.dev/tutorials/review-theme-store-requirements), accessibility best practices, and of course our own experience in developing themes for more than 15 years now.

Our goal is to make this project the most completed, robust, and of course the most awesome Shopify theme for the Bootstrap framework.


## Highlighted features:
* Powered by [Bootstrap framework](https://getbootstrap.com/) (v5)
* Developed respecting [Shopify themes requirements](https://shopify.dev/tutorials/review-theme-store-requirements)
* All elements are fully accessible with [aria attributes](https://www.w3.org/WAI/standards-guidelines/aria/)
* No Javascript framework dependencies (e.g. jQuery)
* Support for [native image lazy-loading](https://web.dev/native-lazy-loading/)
* PageSeed score 96/100 [check results](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fks-bootshop.myshopify.com%2F&tab=desktop) 
* All Shopify required homepage sections (~20)
* All Shopify templates (cart, product, etc.) have their corresponding settings
* Product layout option grid or list
* Ajax add to cart
* Recommended products section [Learn more](https://shopify.dev/tutorials/develop-theme-recommended-products)

## Homepage sections
* Carousel
* Featured Products
* Featured Collections
* Cards with image
* Video
* Contact Form
* F.A.Q
* HTML
* Image with text
* Newsletter
* Richtext
* Separator





## Installation
**Note:** Please, make sure you are familiar with [Theme kit](https://shopify.github.io/themekit/), and official documentation before proceeding. We are assuming that at this point you have already installed the Theme Kit.

store with our theme in preview mode.

`theme open`

## Customization
Please don't directly modify theme files as you will lose any changes when you upgrade our theme. The recommended way to handle this is by creating a copy of our theme and then modifying it. Please follow this [official tutorial](https://help.shopify.com/en/manual/online-store/legacy/using-themes/managing-themes/duplicating-themes) to learn more. 


Now, you can compile the `bootstrap.scss` file that you have just modified using the following command:
`npm run bs-css` or `npm run watch` (to continuously watch for changes)

To deploy your changes on your Shopify store run the following Theme Kit command:
`theme deploy` or: `theme watch`

