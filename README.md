# Wordpress Schema Plugin

OTM Homemade Schema (JSON-LD) plugin for Wordpress.

Features:
* places JSON-LD information in website header for spiders to crawl;
* fully compliant with Google recommended schema markup;
* provides contact information about Local Business and can be later extended to other business types;
* provides control over service rating shown on Google by manual means or automatic Testimonial loop;
* provides Testimonial custom post type in menu and star rating system below the editor;
* adds settings page with generous recommendations for better crawling, some fields have sane defaults, others default to best available alternative;

Todo:
* create Schema Person for one and/or more attorneys for even better Google™ Rich Snippets;
* provide templates and loops for Testimonial post type;
* create shortcode for star rating;
* allow more Business types;
* optimize code, search for security issues;

### Installing

* drop this plugin in /wp-content/plugins/;
* activate from Wordpress Plugin manager;
* complete setup in "schema settings" menu;

## Running the tests

* this plugin should not conflict with other common plugins;
* if used with Bustr theme, will use existing testimonials for automatic aggregation;
* tested with php 7.0;
* works with Wordpress 4 and up;

## Built With

* [Schema rating markup](https://schema.org/Rating);
* [Schema structure testing tool](https://search.google.com/structured-data/testing-tool);
* [wp-plugin-template](https://github.com/hlashbrooke/WordPress-Plugin-Template);


## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).
