=== cct_webapi ===
Contributors: rag-guay
Donate link: http://customct.com
Tags: webapi
Requires at least: 3.2
Tested up to: 3.4
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin creates a custom post type called API. When you create an API post, all of the content will be executed as PHP code just before the theme stuff is executed in WordPress. 

== Description ==

Many times when a site powered by WordPress wants to supply a Web API for their site, they will work outside of WordPress using either PHP or Ruby on Rails. Then they have to write their own functions to get to the information inside the database for their WordPress site. I always thought that was a little backwards. That is why I wrote the Web API plugin for WordPress.

With the Web API plugin, you no longer have to do that. This plugin creates a custom post type called API. When you create an API post, all of the content will be executed as PHP code just before the theme stuff is executed in WordPress. Therefore, you have full access to all the WordPress PHP functions to create whatever you want: JSON output, HTML sniplets, full HTML pages without any of the sites theme or code, or anything else you can imagine. After the code on the page is executed, then the PHP session will be ended.


== Installation ==

1. Upload `cct_webapi.zip` to the `/wp-content/plugins/` directory and unzip.
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Create a new API post type with you PHP code and you are running!

== Frequently Asked Questions ==

None.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the directory of the stable readme.txt, so in this case, `/tags/4.3/screenshot-1.png` (or jpg, jpeg, gif)
2. This is the second screen shot

== Changelog ==

= 1.0 =
* First Version.
