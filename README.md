# Awesome WooCommerce [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome WooCommerce resources — APIs, developer tools, extensions, themes, payments, performance and learning materials for merchants, developers and agencies on WordPress.

Everything for building and running a store with [WooCommerce](https://woocommerce.com), the open-source ecommerce platform for WordPress — from the REST and Store APIs to extension development, block themes, WooPayments, performance tuning and SEO. Maintained by the team behind [Mention Network](https://mention.network); see also [awesome-agentic-commerce](https://github.com/MentionNetwork/awesome-agentic-commerce).

## Contents

- [Official Resources](#official-resources)
- [APIs & SDKs](#apis--sdks)
- [Developer Tools](#developer-tools)
- [Extension Development](#extension-development)
- [Themes](#themes)
- [Plugins](#plugins)
- [Learning Resources](#learning-resources)
- [Communities](#communities)
- [Top Articles & Guides](#top-articles--guides)

## Official Resources

- [WooCommerce Blog](https://woocommerce.com/blog/) - Official blog publishing release announcements, merchant guides and product news.
- [WooCommerce Code Reference](https://woocommerce.github.io/code-reference/) - Auto-generated API reference of WooCommerce classes, functions and hooks.
- [WooCommerce Developer Blog](https://developer.woocommerce.com/blog/) - Engineering-focused blog with release notes, roadmap posts and developer announcements.
- [WooCommerce Developer Documentation](https://developer.woocommerce.com/docs/) - Official developer hub for building extensions, themes and integrations.
- [WooCommerce on WordPress.org](https://wordpress.org/plugins/woocommerce/) - Canonical listing for the free WooCommerce core plugin with downloads and changelog.
- [woocommerce/woocommerce](https://github.com/woocommerce/woocommerce) - Actively maintained monorepo containing WooCommerce core, packages and dev tooling.
- [WooCommerce.com](https://woocommerce.com/) - Official home of WooCommerce covering products, pricing and enterprise offerings.

## APIs & SDKs

- [WooCommerce REST API - JavaScript](https://github.com/woocommerce/woocommerce-rest-api-js-lib) - Official JavaScript/Node client for the WooCommerce REST API.
- [WooCommerce REST API - PHP](https://github.com/woocommerce/wc-api-php) - Official PHP client for the WooCommerce REST API, distributed via Composer.
- [WooCommerce REST API - Python](https://github.com/woocommerce/wc-api-python) - Official Python wrapper for the WooCommerce REST API, installable via pip.
- [WooCommerce REST API Docs](https://woocommerce.github.io/woocommerce-rest-api-docs/) - Reference for the authenticated WooCommerce REST API covering endpoints, auth and webhooks.
- [WooCommerce Store API](https://developer.woocommerce.com/docs/apis/store-api/) - Documentation for the unauthenticated Store API powering cart, checkout and product front-end.

## Developer Tools

- [Action Scheduler](https://github.com/woocommerce/action-scheduler) - Scalable background job queue for WordPress maintained by Automattic and bundled with WooCommerce.
- [create-woo-extension](https://github.com/woocommerce/woocommerce/tree/trunk/packages/js/create-woo-extension) - Official scaffolding package that generates a ready-to-build WooCommerce extension.
- [Query Monitor](https://wordpress.org/plugins/query-monitor/) - Developer tools panel surfacing database queries, hooks, REST calls and PHP errors.
- [WooCommerce Blocks](https://github.com/woocommerce/woocommerce/tree/trunk/plugins/woocommerce/client/blocks) - Source for the cart, checkout and product Gutenberg blocks, developed inside the core monorepo.
- [wp-env](https://github.com/WordPress/gutenberg/tree/trunk/packages/env) - Official zero-config Docker-based local WordPress environment tool.
- [WP-CLI](https://github.com/wp-cli/wp-cli) - Command-line interface for managing WordPress and WooCommerce sites.

## Extension Development

- [Action Scheduler Docs](https://actionscheduler.org/) - Documentation for the Action Scheduler job queue library, covering usage, WP-CLI and the API.
- [Extension Development Best Practices](https://developer.woocommerce.com/docs/extensions/best-practices-extensions/extension-development-best-practices/) - Official guidance on coding standards, compatibility and quality for extensions.
- [Get Started Building Extensions](https://developer.woocommerce.com/docs/extensions/getting-started-extensions/) - Entry-point guide covering core concepts, setup and best practices for extension development.
- [How to Build Your First Extension](https://developer.woocommerce.com/docs/extensions/getting-started-extensions/building-your-first-extension/) - Step-by-step tutorial for scaffolding, building and running a first extension.
- [WooCommerce Hooks Reference](https://woocommerce.github.io/code-reference/hooks/hooks.html) - Reference listing of WooCommerce action and filter hooks across templates and core classes.

## Themes

- [Checkout Block](https://woocommerce.com/document/woocommerce-store-editing/customizing-cart-and-checkout/checkout-block/) - Documentation for the block-based Checkout, its inner blocks and customization options.
- [Classic Theme Developer Handbook](https://developer.woocommerce.com/docs/theming/theme-development/classic-theme-developer-handbook/) - Official guide to integrating WooCommerce into classic themes via hooks and template overrides.
- [Storefront (GitHub)](https://github.com/woocommerce/storefront) - Actively maintained source repository for the Storefront theme.
- [Storefront (WordPress.org)](https://wordpress.org/themes/storefront/) - Free flagship WooCommerce theme built by the core team with deep integration.
- [Twenty Twenty-Five](https://wordpress.org/themes/twentytwentyfive/) - Current WordPress default block theme, compatible with WooCommerce block cart and checkout.

## Plugins

The most popular, actively-maintained WooCommerce and WordPress plugins, grouped by use case.

### Payments

- [WooCommerce PayPal Payments](https://wordpress.org/plugins/woocommerce-paypal-payments/) - All-in-one gateway offering PayPal, Venmo, Pay Later and card payments.
- [WooCommerce Square](https://wordpress.org/plugins/woocommerce-square/) - Official Square integration that processes payments and syncs inventory with Square POS.
- [WooCommerce Stripe Gateway](https://wordpress.org/plugins/woocommerce-gateway-stripe/) - Official Stripe gateway accepting cards, digital wallets and buy-now-pay-later methods.
- [WooPayments](https://wordpress.org/plugins/woocommerce-payments/) - WooCommerce-native gateway to accept cards with no monthly fees, built by Woo.

### Email & Marketing Automation

- [FunnelKit Automations](https://wordpress.org/plugins/wp-marketing-automations/) - Marketing automation and CRM engine for cart recovery, follow-ups and email sequences.
- [Klaviyo](https://wordpress.org/plugins/klaviyo/) - Marketing automation powering personalized email and SMS using WooCommerce customer data.
- [Mailchimp for WooCommerce](https://wordpress.org/plugins/mailchimp-for-woocommerce/) - Official integration syncing customer and purchase data for campaigns and cart recovery.
- [MailPoet](https://wordpress.org/plugins/mailpoet/) - WordPress-integrated email tool for newsletters, subscribers and automated campaigns.

### SEO

- [All in One SEO](https://wordpress.org/plugins/all-in-one-seo-pack/) - Widely used SEO plugin with schema markup, XML sitemaps and keyword tracking.
- [Rank Math SEO](https://wordpress.org/plugins/seo-by-rank-math/) - AI-powered SEO plugin with content optimization, schema and Search Console integration.
- [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - Comprehensive SEO plugin with real-time content analysis and schema optimization.

### Reviews & UGC

- [Customer Reviews for WooCommerce](https://wordpress.org/plugins/customer-reviews-woocommerce/) - Sends automated post-purchase email reminders to collect verified product reviews.
- [Site Reviews](https://wordpress.org/plugins/site-reviews/) - Lets visitors submit star ratings and reviews shown like Amazon, TripAdvisor and Yelp.
- [Yotpo Reviews](https://wordpress.org/plugins/yotpo-social-reviews-for-woocommerce/) - Collects and showcases reviews, photos and Q&A to build trust and lift conversions.

### Subscriptions & Memberships

- [Paid Memberships Pro](https://www.paidmembershipspro.com/) - Restricts content and manages member subscriptions with recurring payments and registration.
- [WooCommerce Memberships](https://woocommerce.com/products/woocommerce-memberships/) - Restricts content and product access to members with discounts and drip-fed content.
- [WooCommerce Subscriptions](https://woocommerce.com/products/woocommerce-subscriptions/) - Enables recurring payments so customers can subscribe on a weekly, monthly or annual basis.
- [YITH WooCommerce Subscription](https://yithemes.com/themes/plugins/yith-woocommerce-subscription/) - Sells subscription-based products and services with recurring payments and free trials.

### Bookings & Appointments

- [Amelia](https://wordpress.org/plugins/ameliabooking/) - Automates appointment scheduling and event management for multiple business types.
- [Bookly](https://wordpress.org/plugins/bookly-responsive-appointment-booking-tool/) - Online scheduling and appointment booking with custom forms, calendars and notifications.
- [WooCommerce Bookings](https://woocommerce.com/products/woocommerce-bookings/) - Lets customers book appointments, make reservations or rent equipment through a store.

### Product Management & Custom Fields

- [Advanced Custom Fields](https://wordpress.org/plugins/advanced-custom-fields/) - Adds custom fields, post types and taxonomies to WordPress content without code.
- [Advanced Product Fields for WooCommerce](https://wordpress.org/plugins/advanced-product-fields-for-woocommerce/) - Adds product option fields that let customers personalize products and adjust pricing.
- [Meta Box](https://wordpress.org/plugins/meta-box/) - Developer framework for building custom fields and dynamic content with 40+ field types.
- [Variation Swatches for WooCommerce](https://wordpress.org/plugins/woo-variation-swatches/) - Converts variation dropdowns into color, image and button swatches.

### Page Builders

- [Beaver Builder](https://wordpress.org/plugins/beaver-builder-lite-version/) - Front-end drag-and-drop page building for responsive WordPress layouts without code.
- [Divi](https://www.elegantthemes.com/gallery/divi/) - Visual drag-and-drop theme and page builder with on-canvas editing and design systems.
- [Elementor](https://wordpress.org/plugins/elementor/) - No-code drag-and-drop page builder for designing WordPress sites visually.
- [SeedProd](https://wordpress.org/plugins/coming-soon/) - Builds landing pages, coming-soon pages and maintenance mode pages via drag-and-drop.

### Search & Filtering

- [Advanced Woo Search](https://wordpress.org/plugins/advanced-woo-search/) - AJAX product search across multiple fields with relevance scoring and fuzzy matching.
- [FacetWP](https://facetwp.com/) - Advanced faceted filtering that refines archive and shop content instantly without reloads.
- [FiboSearch](https://wordpress.org/plugins/ajax-search-for-woocommerce/) - Live AJAX product search with SKU search, images and pricing for WooCommerce.

### Performance & Caching

- [LiteSpeed Cache](https://wordpress.org/plugins/litespeed-cache/) - All-in-one site acceleration with server-level caching and front-end optimization.
- [Redis Object Cache](https://wordpress.org/plugins/redis-cache/) - Persistent object cache backend powered by Redis, useful for reducing database load.
- [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/) - Performance framework with page caching, minification, browser caching and CDN integration.
- [WP Rocket](https://wp-rocket.me/) - Premium caching plugin that boosts load speed via page caching, preloading and lazy loading.

### Shipping & Tax

- [Flexible Shipping](https://wordpress.org/plugins/flexible-shipping/) - Table-rate shipping that calculates costs based on cart weight, total or custom rules.
- [WooCommerce Shipping](https://wordpress.org/plugins/woocommerce-shipping/) - Official plugin that prints discounted labels and compares live USPS, UPS and DHL rates.
- [WooCommerce Tax](https://wordpress.org/plugins/woocommerce-services/) - Official plugin that automates sales tax calculation by jurisdiction at checkout.

### Security & Backup

- [Solid Security](https://wordpress.org/plugins/better-wp-security/) - Hardens logins with two-factor authentication, brute-force protection and scanning.
- [UpdraftPlus](https://wordpress.org/plugins/updraftplus/) - Backs up, restores and migrates WordPress sites to cloud storage on a schedule.
- [Wordfence Security](https://wordpress.org/plugins/wordfence/) - Endpoint firewall, malware scanning and login security with real-time threat intelligence.

### Multilingual & Translation

- [Polylang](https://wordpress.org/plugins/polylang/) - Builds multilingual WordPress sites with no limit on the number of languages.
- [TranslatePress](https://wordpress.org/plugins/translatepress-multilingual/) - Front-end visual translation with manual editing or AI-powered automatic translation.
- [WPML](https://wpml.org/) - Builds and manages multilingual WordPress and WooCommerce sites with AI or human translation.

### Analytics

- [Google Analytics for WooCommerce](https://wordpress.org/plugins/woocommerce-google-analytics-integration/) - Integrates GA4 with WooCommerce for conversion tracking and transaction analysis.
- [Metorik](https://metorik.com/) - Real-time analytics, reporting, customer segmentation and email marketing for WooCommerce.
- [MonsterInsights](https://wordpress.org/plugins/google-analytics-for-wordpress/) - Displays Google Analytics reports inside the WordPress dashboard with code-free tracking.

### Import/Export

- [WP All Export](https://wordpress.org/plugins/wp-all-export/) - Exports WordPress and WooCommerce data to custom CSV, XML and Excel files via drag-and-drop.
- [WP All Import](https://wordpress.org/plugins/wp-all-import/) - Imports CSV, XML, Excel and Google Sheets data into posts, fields and WooCommerce products.

## Learning Resources

- [Kinsta WooCommerce Tutorial](https://kinsta.com/blog/woocommerce-tutorial/) - Step-by-step tutorial for installing and configuring WooCommerce on a WordPress site.
- [WooCommerce Getting Started](https://woocommerce.com/documentation/woocommerce/getting-started/) - Official merchant-focused docs for building and configuring a WooCommerce store.
- [WPBeginner WooCommerce Guide](https://www.wpbeginner.com/wp-tutorials/woocommerce-tutorial-ultimate-guide/) - Beginner-oriented tutorial covering store setup, products, payments, themes and launch.

## Communities

- [r/woocommerce](https://www.reddit.com/r/woocommerce/) - Reddit community where merchants and developers discuss setup, troubleshooting and extensions.
- [WooCommerce Support Forum](https://wordpress.org/support/plugin/woocommerce/) - Official WordPress.org support forum with active threads and staff moderation.
- [WooCommerce YouTube](https://www.youtube.com/@WooCommerce) - Official YouTube channel with tutorials, webinars and product walkthroughs.
- [WordCamp Central](https://central.wordcamp.org/) - Hub for WordPress and WooCommerce community events (WordCamps) worldwide.

## Top Articles & Guides

- [Advanced Strategies for WooCommerce Optimization and Scaling](https://kinsta.com/blog/woocommerce-optimization/) - Kinsta, 2026. Scaling with PHP workers, caching, database tuning and headless approaches.
- [Customize the WooCommerce Checkout Page](https://woocommerce.com/posts/customize-woocommerce-checkout/) - WooCommerce, 2024. Merchant-facing overview of checkout customization options, tools and conversion tips.
- [Customizing the Cart and Checkout](https://woocommerce.com/document/woocommerce-store-editing/customizing-cart-and-checkout/) - WooCommerce, 2024. Editing the block-based cart and checkout using the Site Editor and block patterns.
- [Fixing WooCommerce Performance Issues Using Kinsta APM](https://kinsta.com/blog/woocommerce-apm/) - Kinsta, 2026. Diagnosing slow checkouts, admin and product pages with application performance monitoring.
- [High-Performance Order Storage (HPOS)](https://developer.woocommerce.com/docs/features/high-performance-order-storage/) - WooCommerce, 2024. Explains HPOS, its benefits and how to adopt custom order tables.
- [Large Store's Guide to Enable HPOS](https://developer.woocommerce.com/docs/features/high-performance-order-storage/guide-large-store/) - WooCommerce, 2024. Migration guide for enabling HPOS safely on high-volume stores.

## Contributing

Contributions are welcome! Read the [contribution guidelines](contributing.md) first.
