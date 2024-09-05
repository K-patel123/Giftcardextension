# Introduction:

Introducing the ConvertStoreToWeb extension for Bagisto—a transformative solution designed to seamlessly convert your e-commerce store into a fully functional informative business website. Whether you’re transitioning from an e-commerce focus to a more content-driven presence or simply seeking a fresh approach to your online business, this extension offers an effortless way to adapt your existing Bagisto store to a professional, informative website tailored for business owners.

# Unlock Growth with Bagisto's Feature-Packed ConvertStoreToWeb Extension!

* **Seamless Conversion:** Effortlessly transition your existing e-commerce store into an informative website without losing valuable data or functionality.
* **Customizable Footer Pages:** Easily configure and customize essential footer pages such as Services, Team, Our Story, Awards, and Portfolio. Tailor each page to highlight your business’s key information.
* **Enhanced Content Management:** 
Utilize Bagisto’s powerful content management capabilities to manage and update your business information efficiently.
* **Admin Dashboard Integration:** Retain access to Bagisto’s robust admin dashboard, allowing you to manage content, view analytics, and maintain site settings with ease.
* **Customizable Branding:** Adapt the look and feel of your website to match your brand’s identity with customizable themes and design options.
* **Responsive and Mobile-Friendly:** Ensure your informative website looks great and functions smoothly on all devices, including desktops, tablets, and smartphones.
* **SEO Optimization:** Enhance your site’s visibility with built-in SEO tools that help improve search engine rankings and attract more visitors.
* **User-Friendly Navigation:** Provide a seamless browsing experience with intuitive navigation and easy access to important information.
* **Multi-Language Support:** Offer your content in multiple languages to cater to a diverse audience, with support for various translation files.
* **Secure and Reliable:** Benefit from the security and reliability of Bagisto’s platform, ensuring your website is safe and consistently operational.

# Requirements:
* Bagisto: v2.2.2
* PHP: 8.1 or higher
* Composer 2.6.3 or higher

# Installation :
Unzip the respective extension zip and then merge "packages" folder into project root directory

* Goto config/app.php file and add following line under 'providers'

```
Webkul\ConvertStoreToWeb\Providers\ConvertStoreToWebServiceProvider::class
```

* Goto composer.json file and add following line under 'psr-4'

```
"Webkul\\ConvertStoreToWeb\\": "packages/Webkul/ConvertStoreToWeb/src"
```
* Run these below commands to complete the setup:

```
composer dump-autoload
```
```
php artisan optimize:clear
```

* Run the below command to seed the seeders :

```
php artisan db:seed --class=Webkul\\SupplierInfo\\Database\\Seeders\\Attribute\\DatabaseSeeder
```
```
php artisan db:seed --class=Webkul\\SupplierInfo\\Database\\Seeders\\Shop\\DatabaseSeeder
```
```
php artisan db:seed --class=Webkul\\SupplierInfo\\Database\\Seeders\\CMS\\DatabaseSeeder
```

That's it, now just execute the project on your specified domain.
