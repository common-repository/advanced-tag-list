=== Advanced Tag Lists ===
Contributors: blueinstyle
Tags: widgets, plugins, tags
Requires at least: 2.8
Tested up to: 3.1
Stable tag: 1.2

Display your popular tags in list format instead of cloud.

== Description ==

Display your popular tags in list format instead of cloud.
For Themes that do not support Widgets, you can now put this code anywhere in your template:
` <?php if(function_exists('jme_taglist')) { jme_taglist(); } ?> `

Options Include:

* Displaying tags in list format or dropdown menu
* Display tag count
* Order list by most popular or alphabetical 
* Exclude tags and or include/exclude from specific categories.

== Installation ==

1. Download and extract the advanced-tag-list.zip file.
2. Upload the folder containing the Plugin files to your WordPress Plugins folder (usually ../wp-content/plugins/ folder).
3. Activate the Plugin via the 'Plugins' menu in WordPress.
4. Once activated you can go to your Widgets section to add a widget to your sidebar.

== Screenshots ==

1. Widget options

== Changelog ==

= 1.2 =
* Added stand-alone function for themes without Widget functionality.
= 1.1 =
* Added built in caching of tag list for improved performance. Tag list is generated only when a post is added/removed/updated or tag list settings changed, instead of on each page load.
= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.2 =
* Added stand-alone function for themes without Widget functionality.
= 1.1 =
Added built in caching of tag list for improved performance. Tag list is generated only when a post is added/removed or updated, instead of on each page load.