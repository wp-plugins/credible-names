=== Credible Names ===
Contributors: nafsadh
Donate link: http://example.com/
Tags: display name, nickname, user login, unique
Requires at least: 3.0.1
Tested up to: 3.8
Stable tag: 0.1.1
License: Public Domain

Ensure user's nickname and display name are unique and not a display name or nick name or user name of someone else

== Description ==

**Validate Profile Credentials and Names**

In a WordPress site users have multiple names in their profile, the user login, display name and nick name. In a multi-user site, there is often a need to keep them unique. You need to allow users have only credible names, such that,

* All display names are unique
* All nicknames are unique
* No nickname is a display name or login name of another user
* No display name is a nickname or login name of another user

Credible Names is a easy plugin to help you with that.

== Installation ==
The usual!

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php do_action('plugin_name_hook'); ?>` in your templates

== Frequently Asked Questions ==

= is it stable? =
Works for me. But not rigorously tested. 

== Screenshots ==

None

== Changelog ==


== Upgrade Notice ==

== Arbitrary section ==

You may provide arbitrary sections, in the same format as the ones above.  This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation."  Arbitrary sections will be shown below the built-in sections outlined above.