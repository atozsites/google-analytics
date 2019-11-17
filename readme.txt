=== WP Google Analytics ===
Contributors: Atozsites
Tags: analytics, google, google analytics
Requires at least: 3.1
Tested up to: 4.0
Stable tag: 1.4.1

Easily integrate Google Analytics with WordPress to track website statistics

== Description ==

Google Analytics for WordPress makes it easy to track your website's usage, with lots of
helpful additional data.

Features:

* Uses Google's asynchronous tracking method which is faster and more reliable.
* Automatically tracks site speed
* Option to log outgoing links as events
* Option to log 404 errors as events
* Use custom variables in Google Analytics to track additional data on pageviews including:
	* Author
	* Categories
	* Tags
	* Context (such as home, category, post, author, etc)
	* Date
	* Logged in
	* Anything - Use the built-in filter to add your own!
* Allows you to ignore any user roles (administrators, editors, authors, etc)

Collaborate on the plugin: <a href="https://github.com/aaroncampbell/wp-google-analytics">WP Google Analytics</a>

Brought to you by <a href="http://aarondcampbell.com/" title="WordPress Plugins">Aaron D. Campbell</a>

== Installation ==

Use automatic installer.

== Frequently Asked Questions ==

= Where do I put my Google Analytics Code? =

WP Google Analytics has a config page under the settings tab in the admin area
of your site.  You can paste your tracking code from Google into the textarea on
this page.

= How do I track searches? =

WP Google Analytics used to help you track site searches before Google Analytics
started doing this natively.  While we still support tracking searches for
backwards compatibility, this feature has been deprecated and will eventually be
removed.  To track searches in Google Analytics follow this
<a href="http://support.google.com/analytics/bin/answer.py?hl=en&answer=1012264">Google support article</a>.
WordPress uses 's' as the query parameter.

= What tokens are support for custom variables? =

All the built-in tokens are described on the settings page.  You can also add
your own using the 'wga_tokens' filter.

= Can't I just paste the Google Analytics code into my template file? =

Absolutely, however in order to get a better idea of what is going on with your
site, it is often nice to have your own activities ignored, track 404s, searches
and even where users go when they leave your site.  WP Google Analytics lets you
easily do all these things.