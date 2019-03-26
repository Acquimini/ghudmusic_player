=== Ghud Music ===
Tags: audio player, media post
Requires at least: 3.0
Tested up to: 5.0
Requires PHP: 7.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

The plugin is designed to add audio element to posts

== Description ==
The plugin is designed to add audio player element to posts.

==Special Feactures==
This plugin sends client information to 'http://172.104.225.181:8085' to collect usage data
This plugin relies on [ip-api"] http://ip-api.com/" as a service to get geolocation data on the user
a) ip-api terms and use "https://signup.ip-api.com/terms"



== Installation ==
You may install the plugin using one of the three following methods:
1. Unzip file and using an ftp program upload it to the wp-content/plugins/ directory
2. Using the search field in the admin plugins area type in "ghud music" (without quotes) then install from there.
3. Upload zip file through the standard plugins menu.
4. Activate the plugin through the 'Plugins' menu in Wordpress

After activating the plugin, you could start audio elements to posts using this plugin.
You can add this element to post either by using wordpress shortcode or using shortcake ui.
To add this element to post using shortcode, add shortcode "[ghud_music_player]" with the following attributes:
    1 file_path : the path to music file
    2 cover_path: the path to the music thumbnail
    3 artiste: the name of the artiste
    4 title: title of media file
    5 src: src code of music file
To add media element to post using graphical interface, ShortCake plugin is required. For Wordpress versions 5.0 and above,
both ShortCake and tinymce plugins are required.

== Frequently Asked Questions ==
Q) Can I add more than one ghud music audio elements to single post? 
A) No you cannot. You can only add one ghud music element per post

Q) Does this plugin collect data?
A) Yes it does. It sends usage data to 'http://172.104.225.181:8085'

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
