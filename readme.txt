=== Plugin Name ===
Contributors: nickciske
Donate link: http://thoughtrefinery.com/donate/?item=agentpress-permissions
Tags: agentpress, permissions, capability, custom role
Requires at least: 3.5
Tested up to: 3.8.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds custom capabilities for AgentPress Listings so you can control which roles can add/edit/publish listings (using a role manager plugin).

== Description ==

Adds custom capabilities for AgentPress Listings so you can control which roles can add/edit/publish listings.

Also adds a Listings Manager role that can only manage listings (no other post types).

Does not include any role management features. -- you can use a role manager plugin (or code) to manage the custom capabilities added by this plugin.

### Requires:

*   [AgentPress Listings](http://wordpress.org/plugins/agentpress-listings/)
*   StudioPress [Genesis](http://bit.ly/LBYT6f) based theme - required by AgentPress Listings

### Recommended:

*   A role manager plugin like  [Members](http://wordpress.org/plugins/members/), [User Role Editor](http://wordpress.org/plugins/user-role-editor/)

== Installation ==

1. Upload the `agentpress-permissions` folder to the `/wp-content/plugins/` directory or install via the Add New Plugin menu
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Does this only work in the WordPress admin? =

Correct. If you want to restict access to listings on the front end of your site:
* Use the password protection feature built into WordPress
* Use a members plugin (like [Members](http://wordpress.org/plugins/members/) which also has a role manager function) or another plugin designed for this purpose

== Screenshots ==

1. The Listings Manager role added by the plugin
2. Managing the custom capbilties added (using the role manager in the Members plugin)

== Changelog ==

= 1.0 =
* Initial Release