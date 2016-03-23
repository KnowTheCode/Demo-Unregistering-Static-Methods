# Title Enhancer Demo

This one is for demonstrating how to unregister Static Methods in WordPress Event Registry System (as part of the Plugin API).  It goes along with the `remove_filter` and `remove_action` Docx found here:

* [remove_action](https://knowthecode.io/docx/wordpress/remove_action)
* [remove_filter](https://knowthecode.io/docx/wordpress/remove_filter)

## Installation

1. Download it.
2. Put into your `wp-content/plugins/` folder
3. Extract it
4. Go into the `ktc-starter` folder first
5. Run `composer install` in terminal to bring in the dependencies and install Composer locally.
6. Then go into `title-enhancer` folder and repeat step 5.

Installation from GitHub is as simple as cloning the repo onto your local machine.  To clone the repo, do the following:

1. Using PhpStorm, open your project and navigate to `wp-content/plugins/`. (Or open terminal and navigate there).
2. Then type: `git clone https://github.com/KnowTheCode/Demo-Unregistering-Static-Methods`.
3. Go into the `ktc-starter` folder first
4. Run `composer install` in terminal to bring in the dependencies and install Composer locally.
5. Then go into `title-enhancer` folder and repeat step 4.

The font icons used are from ionicons.  You will need to make sure they are enqueued in your theme by doing:

`wp_enqueue_style( 'ionicons', '//code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css', array(), CHILD_THEME_VERSION );`