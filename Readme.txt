=== Spotify Embed Creator ===
Contributors: slowmove
Tags: spotify, spotify play button, shortcode
Requires at least: 3.0
Tested up to: 3.3
Stable tag: 1.0.5

Search for Album or Track on Spotify and create a Spotify Play Button.

== Description ==

Search for Album or Track on Spotify and create a Spotify Play Button by iFrame or Shortcode. Shows up both as a separate admin view as well as on the "edit post" page as a meta box for direct inserting into the content area.

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Enjoy

== Frequently Asked Questions ==

= Can I search thru my playlists? =

Unfortunatly not with the API Spotify has today.

== Screenshots ==

1. The Admin View
2. The "edit post" meta box

== Changelog ==

= 1.0.5 =
* Now doing a more strict search followed by a fuzzy, for more exact result

= 1.0.4 =
* dirname(__FILE__) instead of __DIR__ since it didn't work everywhere

= 1.0.3 =
* Uses file_get_contents() if curl isn't installed

= 1.0.2 =
* Changed name on the shortcode function due to incompatibility with another plugin
* Preview in the edit post meta box as well

= 1.0.1 =
* Banner image for wordpress.org plugin repository
* New Screenshots in English
* Cleaned up the code

= 1.0 =
* first release
