﻿=== Parsi Date ===
Contributors: lord_viper, man4toman, iEhsan.ir
Donate link: http://forum.wp-parsi.com/
Tags: shamsi, wp-parsi, wpparsi, persian, parsi, farsi, jalali, date, calendar, i18n, l10n, Iran, Iranian, parsidate, rtl
Requires at least: 3.6
Tested up to: 4.7
Stable tag: trunk

Persian date support for WordPress

== Description ==

This package is made by Persian developers to bring so much better experience of Persian WordPress. It includes Shamsi (Jalali) calendar, character issues fixes and Right-To-Left fix for WordPress back-end environment.

List of some features:

* Shamsi (Jalali) date in Posts, comments, pages, archives, search, categories
* Shamsi (Jalali) date in Permalinks
* Shamsi (Jalali) date in admin sections such as posts lists, comments lists, pages lists
* Shamsi (Jalali) date in post quick edit, comment quick edit, page quick edit of admin panel
* Shamsi (Jalali) calender widget
* Shamsi (Jalali) archive widget
* RTL and fixed tinymce editor
* Poweful and fast function for fixing Arabic (ي , ك) to Persian (ی , ک)
* Poweful and fast function for Persian numbers
* Low resources usage


== Installation ==

1. Upload plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. To use the archives widget, go to 'Widgets' and choose 'بایگانی تاریخ خورشیدی'
4. To use the calender widget, go to 'Widgets' and choose 'گاه‌شمار تاریخ خورشیدی'

== Screenshots ==

1. Plugin configuration page
2. 'Jalali Date Archives' Widget
3. 'Jalali Date Calender' Widget
4. 'Jalali Date Calender' in action

== Changelog ==
= 2.2.2 =
* Fix error in PHP 7

= 2.2.1 =
* Compatible with WP 4.7
* Fixed: Notice error in acf group page. [#issue](https://wordpress.org/support/topic/need-a-conditional-for-posts-in-wpp_fix_post_date-function/)
* Fixed: Undefined variable `$predate` error in admin lists-fix.php [#issue](https://wordpress.org/support/topic/undefined-variable-predate-in-admin-lists-fix-php/)
* Fixed by: [Mostafa Soufi](https://profiles.wordpress.org/mostafas1990/)

= 2.2 =
* Fixed: Widgets bug causes Deprecated notices in WordPress >= 4.3
* Fixed: the_modified_date() is now in Shamsi. [Reported by Amirhossein Habibi]
* New: Added EDD support to convert prices digits in Persian digits.

= 2.1.7 =
* Fixed timezone bug [Reported by HANNANStd]
* Paragraph style returned to its previous style [Reported by WP-Parsi community]

= 2.1.6 =
* Fixed assets folder issue with community.

= 2.1.5 =
* Added "Droid Sans" & "Roboto" font family to back-end environment & editor by default, also an option for returning that
* Added an option for moving menu item to submenu
* Fixed timezone bug that was set to "Asia/Tehran" by default
* Cleaned codes and documentation

= 2.1.2 =
* Admin menu problem fixed

= 2.1.2 =
* Fix Broken Plugins Update Link (Farsi Locale)

= 2.1.1 =
* Fix Post permalink with custom structure (%category%/%postname%/)

= 2.1 =
* Post Permalink Fixed
* WordPress SEO OpenGraph Dates fixed
* WooCommerce order detail date fixed
* New option for set locale in plugin page settings
* LTR post editor text mode

= 2.0.0-alpha =
* Fully recorded!
* WordPress languages (Persian) files removed
* Persian calendar widget added
* Performance enhanced
* Woocommerce prices problem fixed

= 1.3.5 =
* Wordpress 4.0 ready
* languages updated

= 1.3.4 =
* unix timstamp problems fixed
* languages fixed
* core functions improved

= 1.3.3 =
* editor problems fixed

= 1.3.2 =
* update language files

= 1.3.1 =
* tested on wordpress 3.9 
* added new language files

= 1.3 =
* core function enhanced
* some date function problem fixed

= 1.2 =
* fix memory error
* fix post_where hook

= 1.1 =
* Fix TinyMce text direction
* Fix sitemaps date problems
* New features on plugin settings
* Add persian numbers on the_excerpt function
* Some bugfixs on core functions

= 1.0 =
* Hello world...