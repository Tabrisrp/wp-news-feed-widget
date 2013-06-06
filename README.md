# WP News feed widget

A simple news feed widget with pagination

## Description

WP News feed widget is a simple news feed widget, with pagination, to display the latest news on your website. It will display a list of your latest news titles, with the publication time (if today) or the publication date next to it.

The pagination is set to 10 items per page.

In the widget configuration, you can set the number of posts you want to include, and disable the plugin's css if you want to apply your own.

More features coming in future releases.

## Installation

1. Upload `wp-news-feed-widget` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to 'Appearance' -> 'Widgets' and drop it in your desired widget zone to configure

## Frequently Asked Questions

### What are the css classes to style the widget ?

```/* ul list wrapper */
.wp-newsfw-list {}

/* list items */
.wp-newsfw-item {}

/* ul pager wrapper */
.pager {}

/* pager item */
.pager li {}

/* previous page item */
.prev {}

/* next page item */
.next {
    margin-left: 5px;
}```

### Why can't I configure more options ?
More configuration is coming in future releases.

## Changelog

### 1.0
* Initial release.
