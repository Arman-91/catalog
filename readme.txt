=== Link by XtremelySocial ===

Contributors: timnicholson
Tags: one-column, right-sidebar, left-sidebar, fluid-layout, responsive-layout, custom-header, custom-menu, featured-images, featured-image-header, full-width-template, flexible-header, theme-options, sticky-post, threaded-comments, light, translation-ready, rtl-language-support, custom-background
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=JGJUJVK99KHRE
Requires at least: 4.3
Tested up to: 4.5
Stable tag: 1.4
License: GPLv3
License URI: http://www.opensource.org/licenses/GPL-3.0

Link by XtremelySocial is an adaptation of the "Link" theme by Blacktie.co. It is a modern, fully responsive, "flat" style theme with a nice color palette, big full-width images, and full-width colored sections. The main navigation is an "off canvas" menu that slides in from the right. It includes several beautiful header images for businesses, photographers, musicians, writers and you can upload your own as well. For more information go to http://xtremelysocial.com/wordpress/link/.


== DESCRIPTION ==

The Link theme is a child theme for Flat Bootstrap that moves the header below the navbar, changes the navigation to a button with an "off canvas" menu that slides in from the right. The site title is automatically displayed at the top of this menu.

The theme comes with several beautiful full-width header images and you can also upload your own. The theme is great for business sites, showcasing products, portfolios, or photos. The included header images are designed for designers, businesses, photographers, musicians, and writers / bloggers.

This theme supports a "static" home page and full-width pages and posts, but you can use it in the more traditional blog-style with sidebars.
 
Other features include multiple columns (grid), buttons, icons, labels, badges, tabbed content areas, collapsible content areas, progress bars, alert boxes, carousels (sliders) and much, much more. This is a theme for both users and theme developers with lots of features but without the bloat. 

For more information go to [http://xtremelysocial.com/wordpress/link/].


== LICENSE ==

Link WordPress theme, Copyright (C) 2014 XtremelySocial
Link WordPress theme is licensed under the GPL.

The included header photos are all Public Domain and we are releasing them as GPL along with the theme. They are all from unsplash.com [http://unsplash.com].

The theme was inspired by the "Link" theme by Blacktie.co. They deserve all the credit for how nice the theme looks. [http://www.blacktie.co/]


== INSTALLATION ==

1. Download and install the parent theme, Flat Bootstrap, into your main /wp-content/themes/ directory
2. Download this theme into your main /wp-content/themes/ directory
3. Activate this theme through the 'Appearance' menu in WordPress
4. Read the notes below about how to use this theme


== HOW TO USE THIS THEME ==

= Setting up the Primary and Social Menus =

This theme is designed for the Primary menu to also include links to your social media profiles. So there is an additional menu called "Social Menu". If selected, it will display at the bottom of the "Header Menu".

The Social Menu is intended to display only social media icons instead of text. Add a custom Link to the menu with the URL of social media profile. Then use the included Font Awesome icon set to specify the icon to use. For example, in the "Navigation Label" field, enter one of the following:

`<i class="fa fa-facebook"></i>`
`<i class="fa fa-twitter"></i>`
`<i class="fa fa-google-plus"></i>`

Or any other brand icon from the Font Awesome set.

= Setting up the Home Page =

We think this theme looks great with the home page as a full-width page with a full-screen image at the top. So we have provided a sample home page that you can import into your theme. Use the standard WordPress Import feature and load the /samples/samples.xml file. You can use this sample to build your home page (or any other page on your site).

If you want this page to be your home page, create or edit an existing page to be used for your blog. You don't need any content or special settings on that page as its just a placeholder URL for WordPress to display your blog. Then go into WordPress Appearance -> Customize and set the option for Static Home Page to one of your pages. Assign this page as your blog page.

= Set up the Page Bottom Widget Area =

The original Link HTML theme by Blacktie.co has several "widgets" at the bottom of each page for showing off customer's logos, a call-to-action section, large social media sections, and large map and contact information. So we've set up the theme to default these things until you add your own widgets to the Page Bottom widget area. 

Before adding your own widgets, you can view the page source and copy the text from the sample widgets. Then add normal WordPress text widgets to the Page Bottom widget area and paste in the HTML.

= Set up the Footer =

If you don't need the elaborate samples at the bottom of the page or if you want to add even more content at the bottom of each page, you can add widgets to the Footer widget area. Note that this widget area is already in a container, so you can drop standard widgets in it without a problem. 

= Set up the Footer Menu =

This theme also supports a Footer Menu. We've defaulted a link to the top of the page (with a nice smooth scrolling animation) and a link to your home page there, but you can create your own menu and use that.

= About WordPress Child Themes =

This theme is a standard WordPress "child theme". It comes with only the files that modify the styling, templates, and functions of the parent theme that are needed for this theme.

If you just want to change some of the styling (CSS), we recommend using the WordPress Jetpack plugin for this. It will store your styles in the WordPress database and apply them automatically after the theme's default styles.

If you want to modify the theme further than that, such as to modify page templates, then COPY this theme into your /wp-content/themes directory with a new directory name. Perhaps link-modified or my-link or something like that. You'll also need to change the very first line of the style.css file to change the "Theme Name:" so that you can tell the difference between the original Link theme and your customized one when you are viewing the themes on your site.

By using either of these methods described above (the Jetpack plugin or copying the theme files to a new name), you'll be able to upgrade this theme from WordPress.org to receive bug fixes and new features and incorporate those into your own child theme if you'd like.

You can read more information about how to use child themes on WordPress.org [http://codex.wordpress.org/Child_Themes]

= Additional Theme Features and Usage =

All of the features of the parent theme, Flat Bootstrap, are included in this theme. You can have full-width images at the top of your pages, full-width blog posts (no sidebar), colored sections, buttons, carousels (sliders), and much, much more. 

For more information, see the "How to use our themes" [http://xtremelysocial.com/wordpress/usergide/] and the "Theme Shortcodes" [http://xtremelysocial.com/wordpress/shortcodes/] pages on our website. 


== CHANGELOG ==

= 1.4 = 
* Changed sidebar-pagebottom.php to always fire off the xsbf_pagebottom() filter so that plugins can override what displays there even if a user hasn't added any widgets yet.
* Fixed minor sidebar-pagebottom.php issue to remove an extra </div> which wasn't breaking the layout, but was causing sample widgets to be in their own <div> instead of within sidebar-pagebottom. 
* Load the parent theme's (Flat Bootstrap) style.css from functions.php to improve performance instead of using @include in the theme's style.css. 
* Removed CSS for "after-footer" (footer nav menu and site credits) so it matches the parent theme. This is needed for when Flat Bootstrap v2.0 is released.
* Updated the comments in functions.php to reflect the new option for custom header location (not used by this theme).
* We now completely override the parent theme's xsbf_custom_header_setup() because when v2.0 of Flat Bootstrap is released, it will have its own custom headers. 
* If Jetpack Social Menu is activated, this theme will use that instead of our own. We have also added the phrase "Jetpack" to their social menu so its clear which one is theirs and which one is ours.
* Added footer.php to override the parent theme. This is needed for when Flat Bootstrap v2.0 is released.
* Changed custom header image size to 1600x750px (was 1600x900px) to reflect the largest actual size used by the theme (the home page).
* Removed custom header functions no longer used by WordPress now that its all handled in the Customizer. Specifically xsbf_admin_header_image() and xsbf_admin_header_style().
* Added CSS to remove border around page in preparation for Flat Bootstrap v2.0. This is because this theme extends beyond the page in the page bottom widget area.
* Removed site credit reference to Blacktie.co, but of course still credited here and throughout the code itself.
* Added a blank /images/post-thumbnail-default.png in preparation for Flat Bootstrap v2.0.
* Remove theme support for custom logo coming in Flat Bootstrap v2.0 (for now)
* Updated screenshot to high resolution (1200x900px)
* Added a table of contents to style.css and better organized the sections.

= 1.3 =
* Fixed an issue with the Page Bottom widget area when using a language translation. Adjusted the sidebar-pagebottom.php to call the sidebar by ID rather than name since language translations can change the name.
* Enhanced the CSS to better handle the WordPress Admin Bar when it's in use. Previously, the main menu overlapped it a bit which was ugly and made it harder to navigate. 
* Updated the language translation tag for the social menu. It previously had a different tag ('xtremelysocial') than the rest of the theme ('flat-bootstrap').
* Changed a function name that referred to our spot theme instead of this link theme. It didn't cause any problems, but was confusing to anyone looking at the code.
* Removed reference to Blacktie.co from the site credits that automatically display at the bottom of the theme. They are still credited in this readme.txt file of course.

= 1.2 =
* Enhanced the offcanvas menu so that it now scrolls to allow for more menu items!
* Because of this, up to two levels will now display. The submenu items are indented and aren't forced to uppercase.
* Widened the menu by 40px to look better with longer link titles and when second level menu items are displayed.

= 1.1 =
* Added new custom header that is a city skyline
* Remove content-header.php as the parent theme (Flat Bootstrap v1.4) now handles the logic needed in this child theme. So no need to override it here anymore!
* Remove sidebar-footer.php as no sample widgets are displayed there (they are in sidebar-pagebottom.php) so no need to override the parent theme (Flat Bootstrap v1.4)
* Move the Page Top widget area to below the header image as this looks better.
* Bumped version numbers.
* Includes all the latest enhancements from the parent theme, such as support for portfolios and testimonials, new page templates, full-width embedded videos, expanded color palette, and much more.

= 1.0 =
* Initial version

