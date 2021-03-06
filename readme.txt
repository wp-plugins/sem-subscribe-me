=== Subscribe Me ===
Contributors: Denis-de-Bernardy, Mike_Koepke
Donate link: https://www.semiologic.com/donate/
Tags: subscribe-me, feed, rss, atom, subscribe-button, subscribe, semiologic
Requires at least: 2.8
Tested up to: 4.0
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds widgets that let you display subscribe links to RSS readers such as Feedly or Bloglines.


== Description ==

> *This plugin has been retired.  No further development will occur on it.*

The Subscribe Me plugin will add buttons that let your visitors share your content on [social media sites](http://www.semiologic.com/resources/blogging/help-with-feeds/) such as Bloglines or Google Reader.

Hovering the big RSS buttons will reveal the subscription services. Only major services are included, alongside a Desktop subscription link for those who have the relevant software.

Users of themes that do not support widgets will need to add the following call in their template:

    <php the_subscribe_links(); ?>

The call accepts an optional argument, which sets the widget's title.

= Help Me! =

The [Plugin's Forum](https://wordpress.org/support/plugin/sem-subscribe-me) is the best place to report issues.


== Installation ==

1. Upload the plugin folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress


== Change Log ==

= 5.5.1 =

- Development has ceased on this plugin.  Updated source and readme accordingly
- Updated to use PHP5 constructors as WP deprecated PHP4 constructor type in 4.3.
- WP 4.3 compat

= 5.5 =

- Fix hover when widget is used on a theme that has HTML5 markup.
- WP 4.0 compatibility

= 5.4.3 =

- Use more full proof WP version check to alter plugin behavior instead of relying on $wp_version constant.

= 5.4.2 =

- Clear internal cache upon WP upgrade

= 5.4.1 =

- Fix localization

= 5.4 =

- Use minified javascript file for improved performance
- Code refactoring
- WP 3.9 compat

= 5.3 =

- Added Feedly RSS Reader service
- Removed defunct Google Reader service
- WP 3.8 compat

= 5.2 =

- WP 3.6 compat
- PHP 5.4 compat

= 5.1.1 =

- Removed What's This? help item

= 5.1 =

- WP 3.5 compat
- Removed obsolete newsgator service

= 5.0.2 =

- Fix occasional invalid HTML on manual calls

= 5.0.1 =

- Apply filters to permalinks
- Fix cache flushing

= 5.0 =

- Complete rewrite
- WP_Widget class
- Drop all options except title (nofollow is always enabled)
- Smaller, better list of services
- Use jQuery, insert script in footer
- Localization
- Code enhancements and optimizations
