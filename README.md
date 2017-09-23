YeNom
=====

Project Page for YeNom - A cash recording utility on iOS.

# Description

It is a simple tool which records your daily spending.

[__View In App Store__](https://itunes.apple.com/us/app/yenom/id1120637689?ls=1&mt=8)

# Usage

__Root View__:

  - Pull the table view down / up and hold a while (time interval can be changed in Settings - General - Delay Time) to open the record setting view for income / expenses;
  - 3D Touch on icon is available, you can add Income / Expense directly from home screen.

__Keyboard for Record Amount Field__:

  - __Delete Backward__: Swipe RIGHT on keyboard or text field;
  - __Recover Backward__: Swipe LEFT;
  - __Calculation__: Include simple calculation.

__Tag View__:

  - Show tags list by pressing the tag area below record amount field;
  - Show tags searching field by pressing the tag area again in tags list view;
  - Press zero count tag's "+" button can convert the tag into category, and you can select tags for this category;
  - In Settings - General - Tag Chain, you can set chain tags;
  - Tags summary report can be found by pressing Pie Chart in report view.

__Report__:

  - By pressing records month section, you can get report for related month, swipe up / down to swich to next / previous month;
  - For the report in main menu, you can view reports in expected date range.

__Data Management__:

  - __Settings - LDM - Import__: You can import data from CSV via API (will add more doc about it in the future);
  - __Settings - LDM - Export__: You can export local data as CSV or PDF;
  - __Settings - Data Sync - Synchronization__: You can use iCloud sync for multiple devices sync, sync history will be available when it's ON;
  - Photos are stored in Album named "__YeNom__".

# Change Log

__v3.4.1 @ 2017-09-22__

  - Introduce "Summary Widget" extension.     

__v3.3.2 @ 2017-09-14__

  - BUGFIX: Settings - Feedback - "Custom User Info" view's name fields cannot be saved.

__v3.3.1 @ 2017-08-29__

  - Add "Balance" column for exported Account Report;  
  - Remove category management in original record’s tag selection view.  

__v3.3.0 @ 2017-08-23__

  - New independent tag management view (provided in main menu, between Account & Report);  
  - Sort accounts by name;  
  - Bugfix for Sync: Create tag w/ same name but different record type will lead merging error.  

__v3.2.4 @ 2017-07-15__

  - Support custom date range selection for report view & data export view;  
  - Update report view's records count info when filter records by type;
  - Some UI fine-tunes.  

__v3.2.3 @ 2017-07-05__

  - Fix issue: Cannot select last three accounts that beyond device screen height.

__v3.2.1 @ 2017-06-29__

  - Optimize record date picker;
  - Make "Package & Compress" as an optional way to mail exported reports.

__v3.2.0 @ 2017-06-27__

  - Support specific currency setting for different accounts;
  - Support custom encoding format for exporting report;
  - Support tag name & amount sorting in tags report (by tapping on section title);
  - Remove original tags filter view, and support it in tags report;
  - Reflect records w/o any tag in reports;
  - Optimise report date range selection component;
  - Optimise report charts' preview indicator;
  - Fix crash in save step whenever new account or tag name contains single quote;
  - Some other bug fixes;
  - Update lowest support version to iOS 9.

__v3.1.10 @ 2017-04-25__

  - Fix issue: Third party keyboard conflicts w/ default record number keyboard;  
  - Update help view for record number keyboard;  
  - Support zero amount record.

__v3.1.9 @ 2017-04-13__

  - Fix issue: Cannot create non-English tag;  
  - Fix some typos.

__v3.1.7 @ 2017-03-10__

  - Fine-tune record edit view;  
  - Add more logs for "Data Sync Debug Mode".  

__v3.1.6 @ 2017-03-08__

  - Support currency format setting (Settings - General - Currency Format);  
  - Optimise iCloud Sync;  
  - Optimise layout for different devices.  

__v3.1.4 @ 2017-02-20__

  - Introduce "Data Sync Debug Mode" (Settings - Data Sync - Synchronization);  
  - Use compressed ZIP file as attachment for mailing report;
  - Support exporting multiple reports at same time;
  - UI fine-tuned.

__v3.1.2 @ 2017-01-25__

  - Support multiple accounts;
  - Support grouping tags into category;
  - Support tag chain;
  - Improve report;
  - Support exporting report as CSV;
  - Improve record photo related func;
  - Improve record date picker;
  - Support record & tag searching;
  - Introduce new iCloud Sync func;
  - Support 3D touch to add record from home screen;
  - Improve UI & performance;
  - etc.

__v3.0.0 @ 2014-01-09__

  - Fix bugs on iOS7;
  - Unlock "Full Features".

__v2.4.2 @ 2013-02-25__

  - Fix bug: Remove date picker when cancel from date setting state;
  - Enable to export records date as a PDF file (included in "Full Features" package).

__v2.3.1 @ 2013-02-14__

  - Modify style for record setting view;
  - Add custom date picker (include in "Full Feature" package).

__v2.2.5 @ 2013-01-24__

  - Re-enable to view the income/expenses count for the selected month/day.

__v2.2.4 @ 2013-01-10__

  - Update UI;
  - Modify statistics view;
  - Fix bug for UI blocking after added a new record (iOS 6);
  - Fix bug for background freshing between empty data & none-empty data situation.

__v2.1.5 @ 2012-12-21__

  - Fix title for keyboard help view;
  - Enable item modification (included in "Full Features" package);
  - Generate record without inserting into database before confirm the settings;
  - Fix a crash bug after inserted a new record for a new month;
  - Change method for deleting item: Select the item, swipe to right or left to confirm delete.

__v2.0.1 @ 2012-12-05__

  - Reconstruct code of basic functions and optimize performance;
  - Fix bug for item's value color changing in settings table view;
  - Part style & feature modification.

__v1.9.5 @ 2012-11-21__

  - Enable date modification (included in "Full Features" package);
  - Asynchronously load image after taking the photo;
  - Fix localization in action sheet for deleting the photo;
  - Modify the size of default photo;
  - Modify photo preview style (full screen, enable scrolling & zooming, etc).

__v1.8.3 @ 2012-10-23__

  - Fix layout for iPhone 5's 4" screen;
  - Fix a bug on iOS6: UITextFieldTextDidChangeNotification will not be sent when textfield was changed programmatically.

__v1.7.11 @ 2012-09-19__

  - Change system keyboard to customize keyboard for number pad;
  - Add basic calculation function for number pad;
  - Change icon;
  - Optimize performance;
  - Reset selected cell index after remove the tag item;
  - Offer an action sheet to user for confirming to delete the tag;
  - Modify options (Fast, Normal, Slow) for delay time setting;
  - Fix navigation bar back button's state: back to previous view from donate view when loading timeout;
  - Enable purchase for 'Full Features';
  - Fix record tag's frame width;
  - Modify default keyboard style for tag adding;
  - Allow to enter 'Free Code' to turn 'Full Features' on;
  - Change navigation bar style for mail view.

__v1.6.8 @ 2012-08-23__

  - Modify statistics view: support month & day statistics;
  - Support year setting in statistics view;
  - Optimize performance;
  - Rename "Delay Time for Swipe Gesture" to "Delay TIme" in settings view;
  - Allow user to delete all records for one month;
  - Fix bug: Delete the data at 00:00 of next month incorrectly while deleting one month's data;
  - Fix bug for statistics: Double count for 00:00 and 24:00;
  - Fix bug: Selecting a row in one section leads the same row of another section to expand either.

__v1.5.4 @ 2012-08-23__

  - Enable to delete a single record;
  - Add iCloud;
  - Allow user to toggle iCloud service.

__v1.4.3 @ 2012-08-09__

  - Add In-App Purchase for donation;
  - Part UI modified;
  - Remove `+` / `-` button in the root view, use drag-and-hold gesture only;
  - Fix a bug: Adding the first record leads the font size to be wrong;
  - Add some help views for gestures.

__v1.2.4 @ 2012-07-26__

  - The first released version on App Store.

# Feedback

Please email your comments, suggestions and questions to `support#kjuly.com`.
Or you can just post a bug report or a feature request [__HERE__](https://github.com/Kjuly/YeNom/issues/new).

Thank you! :)

