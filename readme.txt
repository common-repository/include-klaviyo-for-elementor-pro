=== Include Klaviyo for Elementor pro ===
Contributors: 
Donate link: paypal.me/nguyenminhthong
Tags: Klaviyo, Elementor Pro
Requires at least: 4.3
Tested up to: 6.6.2
Stable tag: 5.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

 Klaviyo's list API integration for Elementor pro form

== Description ==

1. This plug in allow you to add or subscribe users to Klaviyo's list memberships and subscriptions using Elementor pro form.

2. Klaviyo offical website: https://www.klaviyo.com/

3. To achieve this, the pluin using Klaviyo list's API (you can read more here: https://developers.klaviyo.com/en/reference/api_overview)

4. To use this plugin, you will need an API key provide by Klaviyo when using their services. That mean when using this pluign you are agree with Klaviyo's Legal, Terms, & Policies here: https://www.klaviyo.com/legal

5. Known Issues:
**Fatal Error Call to a member function get_modules() on null:**
    * Temporary deactivate the plugin
    * update Elementor/Elementor Pro or run Elementor Database Updater
    * Reactivate my plugin again

== Installation ==

1. Best is to install directly from WordPress. If manual installation is required, please make sure that the plugin files are in a folder named “include-elementor-klaviyo” (not two nested folders) in the WordPress plugins folder, usually “wp-content/plugins”.

2. Activate the plugin through the 'Plugins' menu in WordPress

3. Detail guide to setup the plugin here: https://nguyenminhthong.net/resource

4. Known Issues:
**Fatal Error Call to a member function get_modules() on null:**
    * Temporary deactivate the plugin
    * update Elementor/Elementor Pro or run Elementor Database Updater
    * Reactivate my plugin again

== Frequently asked questions ==

=How to get your Klaviyo API key?= 
follow the guide here: https://help.klaviyo.com/hc/en-us/articles/115005062267-Manage-Your-Account-s-API-Keys

=How to get Klaviyo list's ID?= 
follow the guide here: https://help.klaviyo.com/hc/en-us/articles/115005078647-Find-a-List-ID#find-your-list-id0

=How to setup the pluin?= 
follow the guide here: https://nguyenminhthong.net/resource

=Known Issues=
1. Fatal Error Call to a member function get_modules() on null:
    * Temporary deactivate the plugin
    * update Elementor/Elementor Pro or run Elementor Database Updater
    * Reactivate my plugin again

== Screenshots ==

1. Select Klaviyo in Elementor form after submit actions

2. Plugin will need Klaviyo API key and List ID to work

3. Way to get the field's ID

== Changelog ==
=Version 1.0.0=
1. Adding "Source Name" setting
2. Adding First name, Last name settings to automatically merge to Klaviyo list

=Version 1.0.1=
1. Updating guides
2. Add remove space from api key and list ID functions

=Version 1.1.0=
1. Add filter for custom action

=Version 1.1.1=
1. Add filter for phone field enable

=Version 1.1.2=
1. Add option for consent enable

=Version 1.1.3=
1. Add nation code setting

=Version 2.0=
1. Add option for API endpoint

=Version 2.1=
1. Add Debug function for better support

=Version 3.0=
1. Update to working with Klaviyo new API version
2. Fix Fatal Error when run Elementor update

=Version 3.1=
1. Fix **Date added** bug

=Version 3.2=
1. Add form's fields as custom properties to Klaviyo profile

=Version 3.3=
1. Add function allow user to dismiss the notices

=Version 4.0=
1. Allow to update already exists profiles

=Version 4.1=
1. Allow add/subscribe a profile to multi list

=Version 4.1=
1. Adding location settings to automatically merge to Klaviyo list
2. Inprove Debug function

== Upgrade notice ==




