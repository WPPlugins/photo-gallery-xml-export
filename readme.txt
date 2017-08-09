=== Photo Gallery XML Export ===
Contributors: lahrah
Tags: photo, gallery, xml, export, flash
Tested up to: 3.1.1
Version: 1.3
Stable tag: trunk

The plugin generates an XML feed from your Wordpress posts using the excerpt field, permalink and five custom fields of your choosing.

== Description ==

UPDATE: I've written a new plugin that will eventually phase this one out completely. It has all of the same functionality with a couple of extras including support for post attachment's. Check it out here: <a href="http://lauragentry.com/2011/04/15/wordpress-plugin-xml-ify-wordpress-multiple-posts/">XML-ify Wordpress Multiple Posts</a>.

 


== Installation ==

1. Unzip and upload files to your plugins directory.
2. Activate.
3. Choose your settings in the "Photo Gallery XML Export" options page of in Wordpress admin area. 
4. To view your custom XML file, add "?feed=galleryxml" to the end of your feed URL or "/galleryxml" to the end of your blog URL, depending on how your site's feeds are set up. 


== Issues ==

1) The XML declaration is hard-coded to be: ?xml version="1.0" encoding="UTF-8"? … I don’t have any plans to change that unless I get requests for other declarations.

2) You can name most XML elements however you see fit, but right now the parent element is hard-coded to “images” and each blog post parent element is hard-coded to “pic.” I’m hoping to make that customizable in the future.

3) If excerpt field is selected to show but is not populated, the caption pulls from the blog post. This is actually the way Wordpress core is supposed to work, but not entirely ideal. 


== Frequently Asked Questions ==

None so far. Ask away: its.the.general@gmail.com