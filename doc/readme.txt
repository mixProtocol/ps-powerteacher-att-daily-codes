Daily Attendance Codes in PowerTeacher Meeting Attendance

Description
This plugin adds a "Daily" column to the PowerTeacher "Record Meeting Attendance" screen which displays the (non-Null) daily attendance code for the students for the date selected (not always 'Today').

New: Version 1.30 adds the ability to display the AttCode column in the Admin Portal (on the Attendance page accessible from the Teacher Schedules screen).  This can be optionally enabled/disabled via the new Preferences page (accessible by clicking the Plugin Name in the Plugin Management Console and the clicking the "Configure" button ).  v1.20/20190515.01 improved page load times by deferring the attendance query until after the page has rendered.

Note: Versions earlier than 1.11/20190514.01 did not properly display the daily attendance codes for classes other than full year (sections with a TermID not ending in '00').  All users should upgrade to v1.11 or greater.

The code was originally based on Brian Sizer's "Class Attendance with inline daily attendance display" customization from the Exchange, though reworked to link lookup students based on ccid values rather than names.

Release History:
1.30 / 20190605.01 - Optional in admin portal; added prefs screen; improved JSON security
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
To access the Plugin Preferences page
1. From the District Office, navigate to the Plugin Management Dashboard (Start Page > System Administrator > System Settings > Plugin Management Dashboard)
2. Click on the name of the plugin ("Daily AttCodes in PT Meeting Attendance")
3. Click the "Configure" button on the plugin's Setup page