# Useful Links

Quick reference to the official help resources for theme and plugins that powers
Taystee's Burgers. When something in the WP admin
doesn't behave as expected, start with the vendor documentation for that component - it is kept
up to date with the version installed on the site.

---

## Site Stack at a Glance

| Component | Version installed | What it does | Official docs |
| --- | --- | --- | --- |
| WordPress | 7.0.3 | Core CMS and block editor | [wordpress.org/documentation](https://wordpress.org/documentation/) |
| Blocksy (parent theme) | 2.1.49 | Theme, header/footer builders, Customizer | [Blocksy Docs](https://creativethemes.com/blocksy/docs/) |
| Blocksy Companion | 2.1.50 | Adds Blocksy extensions and modules | [Extensions Docs](https://creativethemes.com/blocksy/docs/extensions/extensions-general/) |
| blocksy-child | - | Taystee's Burgers custom theme by Coalition Technologies | [Child Theme Docs](https://creativethemes.com/blocksy/docs/getting-started/child-theme/) |
| Stackable - Ultimate Gutenberg Blocks | 3.19.10 | The page-builder blocks used across all pages | [Stackable Docs](https://docs.wpstackable.com/) |
| Gravity Forms | - | Contact, careers, franchising and rewards forms | [Gravity Forms Docs](https://docs.gravityforms.com/) |
| Gravity Forms reCAPTCHA add-on | 2.2.2 | Spam protection on form submissions | [reCAPTCHA Add-On Docs](https://docs.gravityforms.com/category/add-ons-gravity-forms/recaptcha-add-on/) |
| Yoast SEO | 28.1 | Page titles, meta descriptions, sitemaps, schema | [Yoast Help Center](https://yoast.com/help/) |

> Versions are accurate as of this document's last update. Check **Dashboard → Updates** in WP admin
> for the current numbers.

---

## Stackable - Gutenberg Blocks

Stackable provides the hero sections, columns, icon boxes and cards you edit on every page. See
[WP Blocks](custom-sections.md) in this guide for the site-specific instructions.

- [Documentation home](https://docs.wpstackable.com/) - searchable knowledge base
- [Getting Started](https://docs.wpstackable.com/collection/306-getting-started) - the editor basics, first block, layouts
- [Block library](https://wpstackable.com/blocks/) - what every Stackable block does, with examples
- [Global Settings](https://docs.wpstackable.com/article/463-global-settings) - site-wide colors and typography presets
- [Advanced Guides](https://docs.wpstackable.com/collection/433-advanced-guides) - custom CSS, dynamic content, conditional display
- [Troubleshooting](https://docs.wpstackable.com/collection/312-troubleshooting) - blocks not rendering, layout breaking, styles missing
- [FAQs](https://docs.wpstackable.com/collection/318-faqs)
- [Changelog](https://wpstackable.com/changelog/) - what changed in each release
- [Support](https://wpstackable.com/support/) · [Free community forum](https://wordpress.org/support/plugin/stackable-ultimate-gutenberg-blocks/)
- [Blog & tutorials](https://wpstackable.com/blog/)

---

## Blocksy Theme

Blocksy powers the Customizer, header and footer. See [Theme Settings](index.md) in this guide for the
site-specific walkthrough.

- [Documentation home](https://creativethemes.com/blocksy/docs/)
- [Theme Options](https://creativethemes.com/blocksy/docs/theme-options/theme-options-intro/) - colors, typography, layout, buttons
- [Header Builder](https://creativethemes.com/blocksy/docs/header-elements/header-builder-elements/) - rows, elements, sticky header, mobile menu
- [Footer Builder](https://creativethemes.com/blocksy/docs/footer-elements/footer-builder-elements/) - columns, widgets, copyright
- [Extensions](https://creativethemes.com/blocksy/docs/extensions/extensions-general/) - Companion features such as custom code and mega menu
- [Modules](https://creativethemes.com/blocksy/docs/modules/conditions-module/) - display conditions, hooks, custom post types
- [Theme Blocks](https://creativethemes.com/blocksy/docs/theme-blocks/theme-blocks-getting-started/)
- [Child theme](https://creativethemes.com/blocksy/docs/getting-started/child-theme/) - how `blocksy-child` relates to the parent
- [Troubleshooting](https://creativethemes.com/blocksy/docs/troubleshooting/minimum-system-requirements/)
- [Changelog](https://creativethemes.com/blocksy/changelog/)

> **Important:** never edit the **Blocksy** parent theme files. All customizations belong in
> **blocksy-child**, otherwise a theme update will overwrite them.

---

## Gravity Forms

All site forms are built with Gravity Forms. See [Form](form.md) in this guide for the site-specific
steps.

- [Documentation home](https://docs.gravityforms.com/)
- [Getting Started](https://docs.gravityforms.com/category/getting-started/)
- [Creating a form](https://docs.gravityforms.com/category/getting-started/creating-a-form/)
- [Adding a form to a page](https://docs.gravityforms.com/category/getting-started/add-form-to-site/)
- [Shortcodes reference](https://docs.gravityforms.com/shortcodes/) - the `[gravityform]` attributes
- [Confirmations](https://docs.gravityforms.com/confirmations-listing/) - the thank-you message or redirect after submit
- [Notifications](https://docs.gravityforms.com/notifications/) - who gets emailed on a new submission
- [Entries](https://docs.gravityforms.com/entries/) · [Managing entries](https://docs.gravityforms.com/managing-entries/) - read and export submissions
- [User guides](https://docs.gravityforms.com/category/user-guides/)
- [reCAPTCHA add-on](https://docs.gravityforms.com/category/add-ons-gravity-forms/recaptcha-add-on/) - spam protection settings
- [Official support](https://www.gravityforms.com/help/) (requires an active license) · [Blog](https://www.gravityforms.com/blog/)

---

## Yoast SEO

Controls how pages appear in Google and social shares, plus the XML sitemap at
[/wp-sitemap.xml](https://taystee.coalition.reviews/wp-sitemap.xml).

- [Yoast Help Center](https://yoast.com/help/)
- [First-time configuration](https://yoast.com/help/yoast-seo-first-time-configuration/)
- [Features overview](https://yoast.com/features/)
- [Yoast SEO Academy](https://yoast.com/academy/) - free SEO training courses
- [SEO blog](https://yoast.com/seo-blog/)
- [Community support forum](https://wordpress.org/support/plugin/wordpress-seo/)

---

## WordPress Core

- [WordPress documentation](https://wordpress.org/documentation/)
- [Block editor guide](https://wordpress.org/documentation/article/wordpress-block-editor/) - how the page editor works
- [Pages: add new](https://wordpress.org/documentation/article/pages-add-new-screen/)
- [Menus screen](https://wordpress.org/documentation/article/appearance-menus-screen/) - see also [Menu](menu.md) in this guide
- [Media library](https://wordpress.org/documentation/article/media-library-screen/) - uploading and replacing images
- [Reusable blocks / patterns](https://wordpress.org/documentation/article/reusable-blocks/) - reuse a section across pages
- [Learn WordPress](https://learn.wordpress.org/) - free video lessons and workshops

---

## This Documentation

- [Theme Settings](index.md) - Blocksy Customizer walkthrough
- [Menu](menu.md) - creating and arranging navigation menus
- [Form](form.md) - building forms and embedding them on a page
- [WP Blocks](custom-sections.md) - hero section and copying blocks between pages

---

## Need More Help?

For anything specific to the Taystee's Burgers build - custom code in `blocksy-child`, layout
changes, or a bug that the vendor docs above don't explain - contact [**Coalition Technologies**](mailto:support@coalitiontechnologies.com)
rather than the plugin authors, since the customizations are ours and not part of the stock plugins.
