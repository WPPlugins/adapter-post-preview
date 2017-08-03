<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# Adapter Post Preview

Show your best posts in any widget area. Creates a widget with a post preview, or a carousel of the most recent posts. 

**Contributors:** [ryankienstra](https://profiles.wordpress.org/ryankienstra)  
**Tags:** [widgets](https://wordpress.org/plugins/tags/widgets), [post](https://wordpress.org/plugins/tags/post), [Bootstrap](https://wordpress.org/plugins/tags/Bootstrap), [mobile](https://wordpress.org/plugins/tags/mobile), [responsive](https://wordpress.org/plugins/tags/responsive)  
**Requires at least:** 3.8  
**Tested up to:** 4.7.3  
**Stable tag:** 1.0.3  
**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)  
**Donate link:** http://jdrf.org/get-involved/ways-to-donate/  

## Description ##

* Creates a widget with the post's featured image, headline, excerpt, and link.
* To see the carousel of posts, you must have Twitter Bootstrap 3 and Glyphicons.
* Hides the widget if the post is a single post on the page. For example, if you are on the "Hello World" page, you won't see the widget with a preview of "Hello World."
* The carousel won't show posts that don't have an image.

[![Play video on YouTube](https://i1.ytimg.com/vi/mXSKjlVrh7I/hqdefault.jpg)](https://www.youtube.com/watch?v=mXSKjlVrh7I)

## Installation ##

1. Upload the adapter-post-preview directory to your /wp-content/plugins directory.
1. In the "Plugins" menu, find "Adapter Post Preview," and click "Activate."
1. Add a "Post Preview" widget by going to the admin menu and clicking "Appearance" > "Widgets"
1. Select the post you want. You must have Bootstrap to use the carousel.

## Frequently Asked Questions ##

### What does this require? ###
The carousel of recent posts requires Twitter Bootstrap 3 with Glyphicons.

### How can I change the text in the post link? ###
Put the following in your functions.php file:
`apply_filters( 'appw_link_text' , 'my_appw_link_text' );
function my_appw_link_text( $text ) {
	return 'Keep reading'; // or your own text
}`


## Screenshots ##


## Changelog ##

### 1.0.3 ###
* Security improvements, including widget output.

### 1.0.2 ###
* Fixed height in mobile display.

### 1.0.1 ###
* Fixed a bug in Internet Explorer display of the carousel.

### 1.0.0 ###
* First version.


## Upgrade Notice ##

### 1.0.3 ###
Please upgrade for the security improvements in the widget output.

### 1.0.2 ###
Upgrade if you use the carousel. It now has enough height on mobile devices.

### 1.0.1 ###
No need to update unless you use the carousel. This version fixes its display in Internet Explorer.

