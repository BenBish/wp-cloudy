=== WP Cloudy ===
Contributors: rainbowgeek
Donate link: http://wpcloudy.com/
Tags: weather, forecast, openweathermap, weather widget, hour forecast, local weather, sunset, sunrise, wind, weather map
Requires at least: 3.5.1
Tested up to: 3.9.1
Stable tag: 2.8.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WP Cloudy is a powerful weather plugin for WordPress, based on Open Weather Map API, using Custom Post Types and shortcodes, and much more.

== Description ==

WP Cloudy is a flexible and easy to use weather plugin that allows you to create unlimited different weather using Custom Post Types and Open Weather Map API. 

Create a weather, select your city, choose the options and customize the look in a few clicks.

Embed it anywhere with the shortcode automatically generated by copy and paste in posts, pages, text widgets, or directly in the PHP files of your theme.

With Custom Post Types, you minimize maintenance: change some settings to automatically change all weather with the same shortcode instantly.

<strong>Many features like:</strong><br />
* NEW! Templating system (developers can now create their own template with ease)<br />
* NEW! Autocompletion / suggestion for search cities and countries in admin using Twitter Typeahead (jQuery 1.9 required)<br />
* NEW! Choose number of hours displayed<br />
* NEW! Choose length days names: short or normal<br />
* NEW! 6 new languages supported: Czech, Galician, Vietnamese, Arabic, Macedonian, Slovak<br />
* NEW! Loads Map JS/CSS from your own web host or OWM<br />
* NEW! New paid Add-on : WP Cloudy Geolocation, allows your visitors to get a geolocation weather.<br />
* NEW! Add disable cache button in WP Cloudy settings <br />
* NEW! Cache system to prevent OpenWeatherMap failure<br />
* NEW! Change date format (12h or 24h)<br />
* NEW! Display temperatures unit (C / F)<br />
* NEW! Tabs in WP Cloudy admin panel for better UX<br />
* NEW! New option to enable/disable CSS3 animations<br />
* NEW! Add 14-day forecast <br />
* NEW! New option to display (or not) Sunrise / Sunset<br />
* NEW! New option to display (or not) today date + temperatures (min-max/average) <br />
* NEW! Add WP Cloudy widget dashboard <br />
* NEW! Add a button to integrate the weather shortcode in tinymce editor more easily<br />
* NEW! Now with SVG animated icons (thanks to Noah Blon => http://codepen.io/noahblon )<br />
* NEW! Adding an options panel to bypass options for individual weather<br />
* NEW! Support OpenStreetMap (layers included: current weather, stations, clouds, precipitation, snow, wind, temperature, pressure)<br />
* Retina ready (SVG + CSS3)<br />
* 134 000 cities listed (thanks to OpenWeatherMap)<br />
* Current weather<br />
* Hourly forecasts<br />
* Week forecasts<br />
* Temperatures (current, average, min and max)<br />
* Speed and Wind direction<br />
* Humidity<br />
* Atmospheric pressure<br />
* Cloudiness<br />
* Celsius or Fahrenheit<br />
* Many display languages<br />
* and new features are added regularly<br />

== Installation ==

1. Upload 'wpcloudy' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Click on the new custom post type called Weather and start creating your own weather!

== Frequently Asked Questions ==

= Any questions? =

All the answers are on our site (at least we try): http://wpcloudy.com

== Screenshots ==
1. Create your weather
2. Display options
3. Advanced options
4. Map options
5. Options panel
6. WP Cloudy in action

== Changelog ==
= 2.8.1.2 =
* FIX Shortcode position
= 2.8.1.1 =
* FIX Flexslider JS/CSS conflict
= 2.8.1 =
* FIX Sunrise/sunset is now based on WordPress timezone setting
= 2.8.0.1 =
* FIX Loading template
= 2.8 =
* FIX Bypass number hours forecast in WP Cloudy settings
* NEW! Templating system (developers can now create their own template with ease)
* INFO 300 lines of code reduced
= 2.7.9 =
* NEW! Autocompletion / suggestion for search cities and countries in admin using Twitter Typeahead (jQuery 1.9 required)
* FIX Option display today date + min-max temperatures
= 2.7.8.1 =
* FIX Encoding characters for today day name (thanks to kryvulena)
= 2.7.8 =
* NEW! Choose number of hours displayed
* NEW! Choose length days names: short or normal
* NEW! 6 new languages supported: Czech, Galician, Vietnamese, Arabic, Macedonian, Slovak
* INFO UX improvement in Weather Post type
* FIX Saving settings from radio button in WP Cloudy settings 
* FIX Encoding characters for days names (thanks to kryvulena)
* FIX Disable CSS3 animations now available in individual weather too (not just WordPress Cloudy Settings > Advanced tabs - thanks to batscamp)
* INFO Improved performances by minifying CSS
= 2.7.7 =
* FIX As->XML error
= 2.7.6 =
* NEW! Loads Map JS/CSS from your own web host or OWM
* INFO UX improvement in WP Cloudy settings
* FIX Saving settings from select in WP Cloudy settings 
* FIX 14 days forecast instead of 6 
= 2.7.5 =
* FIX Severals PHP notice
* FIX Warning PHP in Support settings tab
* INFO Improve core performance
* INFO Dequeue wpcloudy-anim.css if animations are disabled
= 2.7.4 =
* FIX Geolocation Add-on
= 2.7.3 =
* NEW! Add disable cache button in WP Cloudy settings 
= 2.7.2 =
* FIX Cache refresh
* NEW! Add clear cache button in WP Cloudy settings
= 2.7.1 =
* FIX Cache refresh with Geolocation Add-on
* FIX Rounding hours temperatures
= 2.7 =
* NEW! New paid Add-on : WP Cloudy Geolocation, allows your visitors to get a geolocation weather.
* NEW! Cache system (finally)!
* NEW! Change date format (12h or 24h)
* NEW! Display temperatures unit (C / F)
* INFO Improved design for WP Cloudy admin panel
* FIX RTE compatibility with WordPress 3.9
* FIX Improve performances in FE / BE
* FIX Severals PHP Notice
* FIX Improve security
* FIX Date format in hours forecast / sunset - sunrise
* FIX rounding problem temperatures.
= 2.6.4 =
* NEW! Tabs in WP Cloudy admin panel for better UX
* NEW! New option to enable/disable CSS3 animations
* FIX Improve security
= 2.6.3 =
* FIX Hide xml errors if Open Weather Map is down
= 2.6.2 =
* FIX Parse error: syntax error, unexpected '}' in wpcloudy-widget.php on line 71
= 2.6.1 =
* FIX Caching system temporarily disabled 
* FIX Improved accuracy for current weather
* FIX Sunrise/sunset time
= 2.6 =
* NEW! Caching system to avoid connection problems to OpenWeatherMap.org using WordPress Transients API
= 2.5.7 =
* NEW! New option to display (or not) Sunrise / Sunset
* NEW! Add 14-day forecast 
* FIX SVG animated icons to current weather with better compatibility with Chrome, Safari, Opera
* FIX some CSS
= 2.5.6 =
* NEW New option to display (or not) today date + temperatures (min-max/average)
* FIX CSS loads in front-end
= 2.5.5 =
* NEW Add WP Cloudy widget dashboard 
* NEW Add a button to integrate the weather shortcode in tinymce editor more easily
* FIX Empty tag <style>
* INFO Optimizing performance in admin and Front-end
* INFO Now fully compatible with WordPress 3.8
= 2.5 =
* NEW Choose the number of days forecast
* FIX Zoom map
* FIX SVG icon map
* INFO Optimizing map performance by loading JS/CSS only if map is enabled
= 2.4 =
* NEW Add custom city title
= 2.3.1 =
* FIX Icon color
= 2.3 =
* NEW Add SVG animated icons to current weather
* NEW Add average temperature
* INFO Optimizing performance in the backend
= 2.2.5 =
* FIX Language
= 2.2.4 =
* FIX Display language
= 2.2.3 =
* FIX Title of widget text  is now displayed above the weather shortcode 
* FIX Forecast unit is now correct
= 2.2.2 =
* FIX Widget text shortcode is now working properly
= 2.2.1 =
* FIX Fatal error
= 2.2 =
* NEW Add option panel to bypass options for individual weather
* FIX "Cannot modify header information - headers already sent" bug
= 2.1 =
* NEW Add custom CSS field
= 2.0 =
* NEW Support OpenStreetMap (layers included: current weather, stations, clouds, precipitation, snow, wind, temperature, pressure) 
* NEW Display/hide current weather 
* FIX some CSS
= 1.2 =
* NEW Support for translations + French version provided
* FIX WP Cloudy icon in admin
= 1.1 =
* Stable release.
= 0.5 =
* First beta release.

