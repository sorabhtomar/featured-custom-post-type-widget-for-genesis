# Featured Custom Post Type Widget for Genesis

WordPress plugin that adds a widget to display Featured Custom Post Types for the Genesis Framework

## Description

WordPress plugin that adds a widget to display Featured Custom Post Types for the Genesis Framework. Supports Custom Taxonomies.

## Requirements

Genesis 2.0+

## Credits
Most of the code in this plugin is from the <a href="http://www.studiopress.com/">StudioPress</a> Genesis Featured Post Widget and I've just added Custom Post Type Support.

Thanks to <a href="https://github.com/ahnlak">Pete Favelle</a> for adding Custom Taxonomy support.

Thank you to <a href-"https://github.com/robincornett">Robin Cornett</a> for all 1.2 and 2.0 improvements and bug fixes.

## Installation

### Upload

1. Download the latest tagged archive (choose the "zip" option).
2. Go to the __Plugins -> Add New__ screen and click the __Upload__ tab.
3. Upload the zipped archive directly.
4. Go to the Plugins screen and click __Activate__.

### Manual

1. Download the latest tagged archive (choose the "zip" option).
2. Unzip the archive.
3. Copy the folder to your `/wp-content/plugins/` directory.
4. Go to the Plugins screen and click __Activate__.

Check out the Codex for more information about [installing plugins manually](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

### Git

Using git, browse to your /wp-content/plugins/ directory and clone this repository:

git clone git@github.com:calliaweb/featured-custom-post-type-widget-for-genesis.git

Then go to your Plugins screen and click Activate.

## Frequently Asked Questions

If you are having styling issues with the columns, try adding this to your stylesheet:

```css
.widget {
	overflow: hidden;
}
```

### Credits
* [Jo Waltham](http://calliaweb.co.uk/)
* with help from [Pete Favelle](https://github.com/ahnlak)
* and [Robin Cornett](http://robincornett.com)

### Changelog

#### 2.0.0
* new feature: display posts in columns within the widget
* bugfix: ajax list now sorts properly

#### 1.2.0
* new option for CPT archive link
* set ajax to load conditionally

#### 1.0.0
* initial release on GH
