# HybridCore

### About HybridCore
HybridCore is a solution that simplifies development by streamlining common tasks used in various web projects. It offers:

- 🚀 **Easy and fast routing engine.**
- 🛠️ **Powerful dependency injection container.**
- 💾 **Variety of back-end solutions for session and cache storage.**

HybridCore is accessible, powerful, and provides the necessary tools for building large and stable applications.

### What's Included?

- 🌍 **Powerful language system:** Supports multiple languages and localizations, allowing for management of various strings and formats.

- 🎨 **Template system (Twig):** A flexible view management system that simplifies customizing and extending the site's design.

- 🔗 **Custom routing with middleware support:** Allows for the addition of middleware for handling HTTP requests and managing access.

- 🔒 **CSRF token:** Protects forms and HTTP requests from Cross-Site Request Forgery attacks by automatically validating the token with each request.

- 📄 **Automatic creation of robots.txt:** Generates and manages the robots.txt file, controlling the site's indexing by search engines.

- 🔍 **Access rights checking for essential files:** Establishes access rights to important files and directories (such as cache and themes), ensuring additional security.

- ⚙️ **Site settings working with cache:** Manages configurations and settings for the site with a caching mechanism, enhancing performance and loading speed.

- 📈 **AnalyticsTracker:** Records user visits and prevents duplicate entries by collecting information on IP addresses, timestamps, and referring URLs, providing traffic analysis for the site.

- ✨ **Extensions:** The system features extensions that can be created by anyone, offering both paid and free options.

### How to Run the Core?

1. ✅ Make sure you have Composer installed on your computer. You can install it by visiting the [official Composer website](https://getcomposer.org/) and following the installation instructions for your operating system.

2. 🚀 Upload the core files to your web hosting and run the `composer install` command in the terminal.

📁 If you are testing the core or using it in a subfolder, please modify the `.htaccess` file. Uncomment the following line:
```
RewriteBase /hybridcore/
```
Replace `/hybridcore/` with the name of the folder where the core is located.
