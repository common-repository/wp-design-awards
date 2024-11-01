=== WP Design Awards ===
Contributors: Konstantinos_Tsatsarounos, zeoz
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=konstantinos.tsatsarounos@gmail.com&item_name=Donation&item_name=Donation&item_number=1&no_shipping=0&no_note=1cy_code=EUR
Tags: Gallery, Design Contest
Requires at least: 3.3
Tested up to: 3.9
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This is the the free version of wordpress plugin, WP Design Awards. Creates the functionality for a web design contest.

== Description ==

This is the the free version of wordpress plugin, WP Design Awards. Creates the functionality for a web design contest.

###Adds two shortcodes:

The css_gallery shortcode for displaying the sites gallery!
[css_gallery category_slug=<category_slug> sites_per_page=9 no_pagination=false]

And the nominee_form for the users to submit their own creations.
[nominee_form]

__Demos:__ 

[Demo 1](http://infogeek.gr/wordpress/design-awards/)
[Demo 2](http://www.wdf.gr/css-gallery)


###Features:

* Adds a sites gallery shortcode with the capability to rate the displayed sites!
* Adds a submission form for visitors and users to submit their own creations
* Adds a custom post type for the sites
* The custom post type has its own template, in which users can rate also!
* Adds a custom taxonomy
* Generates an easy to understand settings page.
* Provides control of the dimensions of accepted featured image
* Provides control of the type of accepted featured image
* Calculates the thumbnail based on a percentage of featured image provided by the admin!
* Provides the choice of default category, if there is one!
* Provides an extra category tag for the users to choose and display to the post page!

[Premium version](http://www.e-xtnd.it/wp-design-awards/)

For more info and support visit: [http://www.e-xtnd.it/wp-design-awards/](http://www.e-xtnd.it/wp-design-awards/)

== Installation ==

1. Download, install and Activate the plugin
2. Create Categories

 _You must create some categories for the wp design awards, custom post type!The most often is: gallery (for general category), nominees and winners for subcategories in gallery! But after all is your choice!
Just go to Design awards, click to the Participants taxonomy, and create few categories!_

 - Gallery
	- Nominees
	- Winners

 __You can choose the default categoy in design awards settings page__

3. Go to the settings page and make your own adjustments and save them.
Before exiting the settings page, for safety, check if your adjustments saved well, if  no, correct them and click again save! Is very important to have correct settings!

4. Setting up pages:
 Of course you can use the shortcodes in posts, your convenience is the very reason for the creation of shortcodes. However is much more convenient to use these shortcodes in pages for easy access!

 ####CSS GALLERY SHORTCODE
For displaying the gallery of a category, you must add a new page/post with the proper shorcode. Add a new page or post and type of copy/page (personally, i have saved the shortcodes as snippets. You don’t need to remember them!):

 [css_gallery category_slug=your_category_of_choice_slug]

 For example:

 [css_gallery category_slug=winners]

 This is the simple version of this shortcode, there are some additional attributes:

 sites_per_page (default 9 post per page)

 no_pagination, accepts values true or false and if true it disables the pagination! The default is false.

 ####NOMINEE FORM SHORTCODE
This is a simple one, you just add a page or post, use the shortcode [nominee_form] and save! So simple!


###WARNING:

__THE PLUGINS FOLDER MUST BE NAMED "design_awards"__

_Also, there is a video! It explains the installation. However is for the premium version! Some things will be a little different!_
http://www.e-xtnd.it/wp-design-awards/

== Frequently asked questions ==

= A question that someone might have =

####How can i change rating image?
At first the image must be transparent in the middle in order to display the colors and 23x20 pixels. You can find the current images in js/stars folder. Create and image and put it inside this folder to be consistant.

After this, go to the functions.php in files directory and locate the line 72 or the first statementa in enqueue_scripts function. Change the name of the image!

####How can i change the colors?

You can change the colors from enqueue_scripts function in files/functions.php under the line 66!

####How can i change the number of the stars and max rate?

Go to js/rating.js folder, under line 26, you can find this paramentres and change them as you wish.

== Screenshots ==

1. All posts view
2. Create and edit post view
3. Gallery
4. Nominee form
5. Settings

__The screenshots are also included in a folder!__


