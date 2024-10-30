=== Mediasite ===
Contributors: ek0nomik
Donate link: 
Tags: mediasite sonicfoundry presentation embed
Requires at least: 3.3
Tested up to: 3.6.1
Stable tag: 1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin allows you to embed Mediasite presentations into your Wordpress pages.

== Description ==

This plugin allows you to embed Mediasite presentations into your Wordpress pages.  By setting up a server you can also take advantage of the built in Mediasite analytics to track who is watching your presentations and on what devices.

== Installation ==

1. Upload the mediasite directory to to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Setup your server(s) on the plugin settings page
4. Add some markup to your page to embed the presentation

== Frequently asked questions ==

= How do I embed a presentation? =

You can embed a presentation by adding some simple markup to your page:

[mediasite server="http://example.mediasite.com" id="71e60c4627b341cc95abf53f673efd791d" width="700" height="450" auth="true"]

= How are the user account passwords stored? =

The plugin stores passwords locally and they are encrypted using Rijndael 256 with an additional salt from your Wordpress installation.  When setting up your server, be sure to use an HTTPS endpoint so no data is sent in plain text over the wire.  That responsibility is on you and is outside the scope of this plugin.

= What are the requirements? =

* Mediasite 6.0 or above
* php-mcrypt
* php-soap