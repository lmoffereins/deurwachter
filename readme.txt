=== Portier ===
Contributors: offereins
Tags: protect, access, restrict, site, blog, user
Requires at least: 4.6
Tested up to: 5.5.1
Stable tag: 1.3.1
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Restrict access to your (multi)site

== Description ==

Restrict access to your site(s) or network for selected users. Additionally show a message at the login screen to notify the user.

The network-activated plugin provides various options to enable network protection, only at the network level or in combination with finegrained site protection.

Supports BuddyPress:
* provide access for selected member types
* provide access for selected user groups

== Installation ==

If you download Portier manually, make sure it is uploaded to "/wp-content/plugins/portier/".

Activate Portier in the "Plugins" admin panel using the "Activate" link. If you're using WordPress Multisite, you can choose to activate Portier network wide for full integration with all of your sites.

This plugin is not hosted in the official WordPress repository. Instead, updating is supported through use of the [GitHub Updater](https://github.com/afragen/github-updater/) plugin by @afragen and friends.

== Changelog ==

= 1.3.1 =
* Added network settings link to a site's admin bar menu
* Changed verbiage of the default access level settings (site and network)
* Changed how allowed BuddyPress member types and groups are displayed in the network sites list table

= 1.3.0 =
* Added option to set a baseline default access level for site and network
* Moved site/network protection details into a admin-bar submenu
* Multisite: Added option to exclude the main site from active network protection
* Multisite: Added admin-bar badge for the network protection status
* Fixed bugs in enforcing the network-only functionality

= 1.2.2 =
* Fixed feed access restrictions that were applied before the current user was checked
* Fixed admin-bar styles in the front-end

= 1.2.1 =
* Updated translations

= 1.2.0 =
* Renamed plugin to Portier because of a naming conflict with another Guard plugin in the .org repository
* Added support for BuddyPress member types

= 1.1.0 =
* Changed Network Sites admin to use a list table
* Added admin pointer for the admin bar Guard icon

= 1.0.0 =
* Initial release
