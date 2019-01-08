# Display Posts - Date View

**Contributors:** billerickson  
**Tags:** shortcode, pages, posts, page, query, display, list, date, month, year
**Requires at least:** 3.0  
**Tested up to:** 5.0  
**Stable tag:** 1.0.0  
**License:** GPLv2 or later  
**License URI:** http://www.gnu.org/licenses/gpl-2.0.html

## Description

[Display Posts](https://displayposts.com) is the simplest way to query and display content in WordPress.

This plugin extends Display Posts by letting you break your content down by month or year. You can use all of the [Display Posts parameters](https://displayposts.com/docs/parameters/) to customize the query.

### Month Listing

`[display-posts display_by_month="true" posts_per_page="999" title="Posts by Month"]`

Use the `display_by_month` parameter to break it down by month. To list all your content, use a high `posts_per_page`, like 999. You can also add an optional `title` to appear above the listing.

### Year Listing

`[display-posts display_by_year="true" posts_per_page="999" title"Posts by Year"]`

Use the `display_by_month` parameter to break it down by year. To list all your content, use a high `posts_per_page`, like 999. You can also add an optional `title` to appear above the listing.

## Filters

If you're a developer, you can use the following filters to customize the markup:

* `display_posts_date_view_heading_tag` - The heading tag used for date headings. Default is h4.
* `display_posts_date_view_heading_class` - The class added to the heading tag. Default is .display-posts-date.
* `display_posts_date_view_month_format` - The date format used for month headings. Default is 'F Y'.
* `display_posts_date_view_year_format` - The date format used for year headings. Default is 'Y'.
