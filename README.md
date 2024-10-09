# Introduction:

The PDF Catalog Generator for Bagisto extension enables store owners to easily generate professionally formatted PDF catalogs from their product listings. This feature is essential for businesses looking to share product information with customers in a clean, organized, and portable format, perfect for offline viewing, distribution, or print.

# Unlock Growth with Bagisto's Feature-Packed ProductPdfGenerate Extension!

* **Generate PDF Catalogs:** Instantly create downloadable PDF catalogs from your product listings.
* **Product Information:** Include essential product details such as name, price, SKU, and images in the generated catalog.
* **Feature Highlights:** 
Highlight product features, price , SKU selling points directly in the catalog.
* **Admin Dashboard Integration:** Retain access to Bagisto’s robust admin dashboard, allowing you to manage content, view analytics, and maintain site settings with ease.
* **Bulk Generation** Generate catalogs for a large number of products with a single click.
* **Multi-language Support:**  Generate catalogs in multiple languages, adhering to Bagisto’s multi-language capabilities.
* **Responsive Design:** Ensure your PDF catalog is responsive and can be viewed on a range of devices, from desktops to mobile.
* **Multi-Language Support:** Offer your content in multiple languages to cater to a diverse audience, with support for various translation files.
* **Downloadable:** Offer your customers a link to download the PDF catalog directly from your store.

# Requirements:
* Bagisto: v2.2.2
* PHP: 8.1 or higher
* Composer 2.6.3 or higher

# Installation :
Unzip the respective extension zip and then merge extracted folder in the packages/Webkul folder

* Goto config/app.php file and add following line under 'providers'

```
Webkul\ProductPdfGenerate\Providers\ProductPdfGenerateServiceProvider::class,
```

* Goto composer.json file and add following line under 'psr-4'

```
"Webkul\\ProductPdfGenerate\\": "packages/Webkul/ProductPdfGenerate/src"
```
* Run these below commands to complete the setup:

```
composer dump-autoload
```
```
php artisan optimize:clear
```

* Run the below command:
```
php artisan vendor:publish --all
```


That's it, now just execute the project on your specified domain.
