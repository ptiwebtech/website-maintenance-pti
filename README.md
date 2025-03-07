Website Maintenance - PTI
Contributors: ptiwebtech
Tags: maintenance mode, coming soon, site offline, under construction
Requires at least: 5.0
Tested up to: 6.7
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

A professional maintenance mode plugin with advanced features, including a coming soon countdown.

== Description ==
Website Maintenance Mode is a simple yet powerful plugin that allows you to put your WordPress site into maintenance mode with a custom message, countdown timer, and background image. Whether you're updating your site or launching soon, this plugin provides all the essential tools to display a professional maintenance or coming soon page.

Features:
✅ Enable/Disable Maintenance Mode – Turn maintenance mode on or off easily.
✅ Full Site or Page-Specific Mode – Apply maintenance mode to the whole site or selected pages.
✅ Customizable Message – Display a custom maintenance message with rich text formatting.
✅ Countdown Timer – Set a timer for when your site will be available again.
✅ Custom Banner & Background – Upload a banner image and set custom background colors.
✅ Google Analytics Support – Add tracking code to monitor visitor activity.
✅ 503 Status Code – Optionally send a 503 response for SEO purposes.
✅ Admin Bypass – Allow logged-in administrators to see the live site.

Filters & Hooks for Developers:
🔹 ptiwmm_maintenance_mode_enabled – Modify whether maintenance mode is enabled dynamically.
🔹 ptiwmm_maintenance_mode_message – Customize the displayed message via a filter.
🔹 ptiwmm_selected_pages_filter – Control which pages are affected by maintenance mode.
🔹 ptiwmm_background_color_filter – Change the background color programmatically.
🔹 ptiwmm_text_color_filter – Adjust the text color dynamically.
🔹 ptiwmm_banner_image_filter – Modify the maintenance mode banner image.
🔹 ptiwmm_ga_tracking_code – Customize the Google Analytics tracking code.
🔹 ptiwmm_status_header_code – Change the HTTP response code (default is 503).

== Installation ==
1. Upload the plugin files to the /wp-content/plugins/website-maintenance-mode/ directory, or install the plugin through the WordPress Plugins screen.
2. Activate the plugin through the Plugins menu in WordPress.
3. Configure the settings under Settings → Maintenance Mode in the WordPress admin panel.
4. Enable maintenance mode and customize your message, banner, and timer as needed.

== Frequently Asked Questions ==
1. How do I exclude specific pages from maintenance mode?
You can use the settings panel to select specific pages or apply the ptiwmm_selected_pages_filter filter in your theme.

2. Will search engines index my maintenance page?
By default, the plugin can return a 503 status code to prevent indexing while in maintenance mode.

3. Can administrators still see the live site?
Yes, logged-in administrators can browse the site normally without seeing the maintenance page.

4. Can I add my own CSS styles?
Yes! You can add custom CSS in the settings panel or override styles using a child theme.

== Screenshots ==

1. Settings Panel – Easily configure maintenance mode settings.
2. Customizable Page – Example of a maintenance mode page with a banner and message.
3. Countdown Timer – Example of a coming soon page with a countdown.

== Changelog ==

= 1.0.0 =
* Initial release

== Upgrade Notice ==

= 1.0.0 =
* First version of the plugin.

== Support ==
For support, visit the plugin's support page on WordPress.org or contact the developer directly.

