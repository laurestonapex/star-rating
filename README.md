# star-rating

### Star Rating APEX Plugin

Oracle APEX plugin for APEX 18 and above. This plugin allows users to capture and render star ratings, with lots of customizable settings. Based on the Rate Yo jQuery plugin: https://rateyo.fundoocode.ninja/

Settings include:

**Star Width**: The width of each star, in pixels.The width of a star is always equal to its height.

**Normal Fill**: The background color for the un-rated part of a star.

**Color Type**: Available options include: Single, MultiColor. If Multicolor is selected, Start Color and End Color must be specified

**Rated Fill**: The color for the rated part of a star. NOTE: This option will not work when Multi Color option is set.

**Number of Stars**: Number of stars to use

**Selection Type**: Available options include: Full Star, Half Star, Precision. When 'Precision' is selected, precision level must be specified

**Spacing**: The amount of space between stars in pixels

**Right to Left**: Render the rating Right to Left.

**Star SVG**: This option can be given during the plugin initialization only, to replace the current star with a custom shape

## Installation

Import file item_type_plugin_laureston_starrating.sql into your APEX application in Shared Components --> Plugins

## Demo Application

https://apex.oracle.com/pls/apex/f?p=96007:1


