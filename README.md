# Awesome WooCommerce [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome WooCommerce resources — APIs, developer tools, extensions, themes, payments, performance and learning materials for merchants, developers and agencies on WordPress.

Everything for building and running a store with [WooCommerce](https://woocommerce.com), the open-source ecommerce platform for WordPress — from the REST and Store APIs to extension development, block themes, WooPayments, performance tuning and SEO. Maintained by the team behind [Mention Network](https://mention.network); see also [awesome-agentic-commerce](https://github.com/MentionNetwork/awesome-agentic-commerce).

## Contents

- [Official Resources](#official-resources)
- [APIs & SDKs](#apis--sdks)
- [Developer Tools](#developer-tools)
- [Extension Development](#extension-development)
- [Themes](#themes)
- [Payments & Checkout](#payments--checkout)
- [Popular Extensions](#popular-extensions)
- [Performance & Hosting](#performance--hosting)
- [SEO & Marketing](#seo--marketing)
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

- [Classic Theme Developer Handbook](https://developer.woocommerce.com/docs/theming/theme-development/classic-theme-developer-handbook/) - Official guide to integrating WooCommerce into classic themes via hooks and template overrides.
- [Storefront (GitHub)](https://github.com/woocommerce/storefront) - Actively maintained source repository for the Storefront theme.
- [Storefront (WordPress.org)](https://wordpress.org/themes/storefront/) - Free flagship WooCommerce theme built by the core team with deep integration.
- [Twenty Twenty-Five](https://wordpress.org/themes/twentytwentyfive/) - Current WordPress default block theme, compatible with WooCommerce block cart and checkout.

## Payments & Checkout

- [Checkout Block](https://woocommerce.com/document/woocommerce-store-editing/customizing-cart-and-checkout/checkout-block/) - Documentation for the block-based Checkout, its inner blocks and customization options.
- [WooCommerce PayPal Payments](https://wordpress.org/plugins/woocommerce-paypal-payments/) - Official PayPal integration offering PayPal, Venmo, Pay Later and card processing.
- [WooCommerce Stripe Payment Gateway](https://wordpress.org/plugins/woocommerce-gateway-stripe/) - Official Stripe gateway built jointly by Stripe and WooCommerce for card and wallet payments.
- [WooPayments](https://wordpress.org/plugins/woocommerce-payments/) - Official WooCommerce-native payment solution for accepting cards and managing payouts in-dashboard.

## Popular Extensions

- [Google for WooCommerce](https://wordpress.org/plugins/google-listings-and-ads/) - Official free extension syncing product feeds to Google Shopping, Search and Ads.
- [Meta (Facebook) for WooCommerce](https://wordpress.org/plugins/facebook-for-woocommerce/) - Official Meta integration for catalog sync and pixel setup across Facebook, Instagram and WhatsApp.
- [Product Add-Ons](https://woocommerce.com/products/product-add-ons/) - Official extension for adding paid or free product customization fields.
- [WooCommerce Bookings](https://woocommerce.com/products/woocommerce-bookings/) - Official extension for selling time- and date-based bookings, appointments and rentals.
- [WooCommerce Subscriptions](https://woocommerce.com/products/woocommerce-subscriptions/) - Official extension enabling recurring payments and subscription products with automatic renewals.

## Performance & Hosting

- [LiteSpeed Cache](https://wordpress.org/plugins/litespeed-cache/) - All-in-one site acceleration plugin with server-level cache and front-end optimization.
- [Redis Object Cache](https://wordpress.org/plugins/redis-cache/) - Persistent object cache backend powered by Redis, useful for reducing database load.
- [W3 Total Cache](https://wordpress.org/plugins/w3-total-cache/) - Host-agnostic performance framework providing page, object and browser caching plus CDN.
- [WP Rocket](https://wp-rocket.me/) - Premium caching and performance plugin widely used to speed up WooCommerce stores.

## SEO & Marketing

- [Google Analytics for WooCommerce](https://wordpress.org/plugins/woocommerce-google-analytics-integration/) - Official plugin connecting WooCommerce to GA4 with ecommerce event and purchase tracking.
- [Klaviyo for WooCommerce](https://wordpress.org/plugins/klaviyo/) - Official Klaviyo plugin for email and SMS marketing powered by store customer data.
- [Mailchimp for WooCommerce](https://wordpress.org/plugins/mailchimp-for-woocommerce/) - Official Mailchimp integration syncing customers and orders for email marketing automation.
- [Rank Math SEO](https://wordpress.org/plugins/seo-by-rank-math/) - Popular SEO plugin offering schema, keyword analysis and WooCommerce product optimization.
- [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) - Widely used SEO plugin with WooCommerce-friendly content analysis, schema and XML sitemaps.

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
