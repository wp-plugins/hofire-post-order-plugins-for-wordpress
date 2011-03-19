=== Hofire Post Order For Wordpress ===
Contributors: Mike Zhang
Donate link: http://www.hofire.com/wordpress-plugins/hofire-post-order-plugins-wordpress/
Tags: custom post order, post order, orderby menu_order
Requires at least: 3.1
Tested up to: 1.0
Stable tag: 1.0

The plugin enables administrator to modify the default order of posts or pages easily in the back-end.

== Description ==

Hofire Post Order Plugin For WordPress is a simple plugin that enables administrator to modify the default order of posts or pages are displayd on your wordpress website.

It is very useful when you want to custom your posts or plages order on the posts or pages list page.

== Installation ==

    1. Download the hofire-post-order.zip file and unzip it to wp-content/plugins folder in your wordpress website;
    2. Activate it through the plugin menu in wordpress back-end;
    3. View posts or pages page, change the order column value what you want and then click the save button behind the 'Order' text.
    4. Add '<?php query_posts('orderby=menu_order&order=ASC'); ?>' code after '<?php if ( have_posts() ) : ?>' on the post or page loop page in your template file.

== Screenshots ==

1. '/tags/1.0/hofire-post-order-larg.gif'

== Changelog ==

= 1.0 =
1. Enables administrator to modify the default order of posts or pages.

== Upgrade Notice ==

= 1.0 =
Upgrade readme.txt.