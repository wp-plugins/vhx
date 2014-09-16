=== VHX Purchase Widget ===
Contributors: VHX
Tags: vhx,movies,video,commerce,e-commerce,widget
Requires at least: 1.0
Tested up to: 4.0
Stable tag: trunk
License: GPL2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds the VHX Purchase Widget to your site and automatically captures buy links to activate the VHX Checkout Widget.

== Description ==
Integrates the VHX Checkout Widget on any Wordpress installation.

Any link on any page pointing to http://yoursubdomain.vhx.tv/buy or http://yourfulldomain.com/buy will be picked up by the widget. Clicks on those links will automatically call the sliding action to purchase on your site.

If you have multiple linked sites on your page (yoursubdomain.vhx.tv and myfriend.vhx.tv), you can additionally set specific data-vhx-site attributes on individual links to override your primary one set on the script tag. It looks like this:

<a href="http://drafthouse.vhx.tv/buy/the-final-member" data-vhx-site>Buy This Movie</a>

== Installation ==
1. Download the plugin
2. Unzip the plugin
3. Upload the entire `vhx-buy-widget` directory into your to the `/wp-content/plugins/` folder
4. Visit your 'Plugins' page inside your Wordpress Admin and Activate the VHX plugin
5. Visit the new "VHX Widget" panel in your sidebar
6. Add your primary VHX subdomain and click Save
7. You're done!

== Frequently Asked Questions ==

= I need help! Can you help me? =

Yep, just shoot us an email at contact+wp@vhx.tv

= I want to link to another VHX site other than my primary domain? Can I do that? =

Yep! Just add "data-vhx-site" on any link to have it trigger the sliding action. Be advised, this may require entering into your Advanced HTML view!

== Screenshots ==

1. The VHX Purchase Widget in action!

== Changelog ==
= 1.0  =
Sliding VHX Purchase Widget Launch!
