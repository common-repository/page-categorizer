=== Page Categorizer ===
Contributors: lumiblog, wpcornerke, sebu4, mosescursor 
Donate link: https://github.com/sponsors/lumumbapl
Tags: category, category in page, tag in page, page archive, pages
Requires PHP: 7.0
Requires at least: 5.4
Tested up to: 6.6.1
Stable tag: 1.1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily add Categories to WordPress Pages.

== Description ==

The **"Page Categorizer"** plugin is a simple yet powerful solution that enables WordPress users to categorize their Pages using the existing Category and Tag taxonomies. By default, WordPress only allows categorizing Posts, but this plugin extends the functionality to include Pages as well.

With this plugin activated, users can easily assign Categories and Tags to their Pages, just like they would for Posts. This feature enhances the organization and structure of website content, making it easier for visitors to navigate and find relevant information.

= Features =

[youtube https://www.youtube.com/watch?v=PyibMA1BjPg]

* **Assign Categories to Pages**: Users can associate one or more Categories with their Pages, providing better content organization and hierarchical structure.
* **Add Tags to Pages**: Similar to Posts, users can add relevant Tags to their Pages, allowing for improved searchability and content discovery.
* **Integrated into the WordPress Admin**: The plugin seamlessly integrates with the WordPress admin interface, providing a familiar user experience. Users can assign Categories and Tags to Pages directly from the Page editing screen, just like they do for Posts.
* **Category and Tag Archives**: The plugin automatically includes Pages in the category and tag archive pages (archive.php and tag.php templates), making it easy for visitors to browse and discover relevant Pages based on their assigned Categories and Tags.
* **Compatibility**: The plugin is compatible with the latest versions of WordPress and follows the WordPress coding standards, ensuring a smooth integration with other plugins and themes.

= What are the benefits?  = 

There are various benefits of adding categories to Pages. You can:

* Embed a Category Based List of Pages 
* Create a Tag-based archive for Pages
* Create a Category based Archive for Pages
* Hide Pages belonging to certain Categories. 
* and so much more.

In case of any issues with the plugin, get support via the [Forums](https://wordpress.org/support/plugin/add-category-to-pages/). 

== Installation ==

This section describes how to install the plugin and get it working.

1. Unzip the archive and upload the entire folder to the /wp-content/plugins/ directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Now Visit the Page editing Screen
4. You can now add Categories to Pages just like you do it in Posts
5. Enjoy. Eat Drink and be Merry !!

== Screenshots ==

1. Page Edit Screen
2. 'Categories' link added under Pages link
 
== Frequently Asked Questions ==

= Why would I need to categorize Pages? =

Categorizing Pages can be beneficial in several ways:

* It helps organize your website content better, making it easier for visitors to find relevant information.
* It allows you to create hierarchical structures and relationships between Pages, similar to how Categories work for Posts.
* It improves discoverability by enabling visitors to browse and discover Pages through category and tag archives.

= Can I assign multiple Categories and Tags to a single Page? =

Yes, absolutely. Just like Posts, you can assign multiple Categories and Tags to a single Page. This allows for more granular organization and tagging of your content.

= Will adding Categories and Tags to Pages affect my existing Post categories and tags? =

No, the plugin creates separate taxonomies for Pages, leaving your existing Post categories and tags untouched. The two taxonomies (for Posts and Pages) are independent of each other.

= Will this plugin work with my existing theme? =

Yes, the plugin is designed to work with any WordPress theme. It integrates seamlessly with the WordPress admin interface and follows the WordPress coding standards, ensuring compatibility with most themes and plugins.

== Changelog ==

= Version 1.1.0 =
* Official initial plugin release

= Version 1.0.1 =
* Plugin release after the 1st review from Plugins Review Team
* Changed the function names to use a more unique prefix:
  - `pc_register_taxonomies` is now `pagecate_register_taxonomies`
  - `pc_modify_archive_query` is now `pagecate_modify_archive_query`
* Updated the Version number to `1.0.1` to reflect the changes.
* The `add_action` calls have been updated to use the new function names.

= Version 1.0.0 =
* Initial Plugin Release

== Upgrade Notice ==

= 1.1.1 =
* A change since the previous version.
