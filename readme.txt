=== Reset Arg Seperator Output ===
Plugin Name: Reset Arg Seperator output
Plugin URI: https://www.wordpress.org/plugins/reset-arg-seperator-output/
Description: Resets the arg_seperator.output PHP ini setting.
Version: 1.0.1
Author: chriscct7
Author URI: http://www.chriscct7.com
Contributors: chriscct7
Donate link: https://www.paypal.me/chriscct7
Tags: arg_seperator.output, Arg Seperator, HostEurope, Host Europe
Requires at least: 1.0.0
Tested up to: 6.6
Stable Tag: 1.0.1

License: GNU Version 2 or Any Later Version

Resets the arg_seperator.output PHP ini setting.

== Description ==

On certain hosts, notably HostEurope, the arg_seperator.output PHP INI setting is set to the html escaped output of an ampersand instead of the default `&`. This leads to issues with plugins that rely on http_build_query arg to generate URLs if they don't hardcode the third parameter. This plugin resets the PHP ini setting.

== Installation ==

1. Activate the plugin
2. It works immediately. There are no settings.

== Frequently Asked Questions ==

= Where are the settings for this plugin =

There are no settings. The plugin is 1 line long, as it just resets the value of the PHP arg_seperator.output ini setting.

== Screenshots ==

There is no UI for this plugin.

== Changelog ==

= 1.0.1: June 28, 2024 =

* Updated Tested-to version


= 1.0.0: November 25, 2016 =

* Plugin introduced
