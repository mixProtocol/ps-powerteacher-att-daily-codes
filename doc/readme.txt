Daily Attendance Codes in PowerTeacher Meeting Attendance

Description
This plugin adds a "Daily" column to the PowerTeacher "Record Meeting Attendance" screen which displays the (non-Null) daily attendance code for the students for the selected date. The same can optionally be enabled for the similar pages on the PowerSchool Admin portal via the plugin's setup page.

New:
Version 1.35 / 20240927.01 resolves an issue that prevented the "Configure" button from displaying in the new Enhanced UI .  All users should upgrade to the latest version.  Version 1.35 also adds the option to display a small comment icon if the daily attendance code includes a comment.  A future version of the plugin will make this clickable so that the teacher can read that comment.
Version 1.36 / 20241002.01 adds support for schools that aren't using meeting attendance to populate daily attendance.
Version 1.38 / 20241017.01 adds optional suport for the substiute portal.  This can be enabled through plugin's preferences page.
Version 1.39 / 20241118.01 fixes a critical issue with PSv24.11 that caused a JSON_ERROR. All users should upgrade to the latest version.


Note: If "Show Multiple Sections" is enabled for the page, there may be a slight delay before the daily codes are displayed.  I hope to address this in a future release.

Release History:
1.40 / 20241118.02 - Better Preference Page descriptions
1.39 / 20241118.01 - Fix for PSv24.11 compatibility
1.38 / 20241017.01 - Substitute portal (optional) through prefs page
1.37 / 20241016.01 - Add initial support for the substitute portal
1.36 / 20241002.01 - Add compatibility for schools not using meeting attendance
1.35 / 20240927.01 - Bugfix for "Configure" button visibility in the new Enhanced UI
1.34 / 20230125.01 - Bugfix for "Configure" button visibility
1.33 / 20210211.01 - Updated for PSv.20.4+ compatibility
1.32 / 20200113.01 - Internal Use, no public release
1.31 / 20190730.01 - Fixed issue with security from previous release
1.30 / 20190605.01 - Admin portal (optional); prefs screen; improved JSON security
1.20 / 20190515.01 - Improved page load times via JSON-based SQL
1.11 / 20190514.01 - Bugfix for sections that were less than full-year
1.10 / 20190506.01 - Support for 'Multiple Sections' and dates other than 'Today'
1.01 / 20190429.02 - Bugfix for PSv.11 compatibility
1.00 / 20190429.01 - Initial Release

Links:
PowerSource: https://support.powerschool.com/exchange/view.action?download.id=991
GitHub: https://github.com/mixProtocol/ps-powerteacher-att-daily-codes

Installation
Install in System > System Settings > Plugin Management Configuration  

Do not unzip the plugin. Install the entire zip file. Be sure to enable the plugin once it's installed.  

If you are updating, you can now click on the Plugin name and then use the Update button, and then browse to the new file and click Submit.  PowerSchool will then load the update and then ask you to enable it.

Instructions
To access the plugin's Preferences page:
1. From the District Office, navigate to the Plugin Management Dashboard (Start Page > System Administrator > System Settings > Plugin Management Dashboard)
2. Click on the name of the plugin ("Daily AttCodes in PT Meeting Attendance")
3. Click the "Configure" button on the plugin's Setup page