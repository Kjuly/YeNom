YeNom
=====

Project Page for YeNom - A cash recording utility on iOS.

# Description

It is a simple tool which records your daily spending.

[__View In App Store__](http://itunes.apple.com/us/app/yenom/id543028543?ls=1&mt=8)

# Usage

__Root View__:

  - Drag the table view down (up) and hold a second to open the record setting view for income (expenses);
  - You can change the delay time in settings view, and there're three options (Fast, Normal, Slow) available.

__Keyboard__:

  - __Delete Backward__: Swipe RIGHT on keyboard or text field;
  - __Recover Backward__: Swipe LEFT;
  - __Calculation__: This feature is included in "Full Features" package, which is needed to purchase.

__Tag View__:

  - Drag the table view down to add a new tag.

__Data Management__:  

  - You can clean all __records__ or __tags__ in settings view's "__Data Management__" section;  
  - Photos are stored in Albums with the name of "__YeNom Photo Lib__";  
**Note**: _Photo related features haven't managed very well right now, sorry for that!_  
  - If iCloud is enabled, data will be stored on remote server. You can get the storage info through your ___"Settings.App" -> "iCloud" -> "Storage & Backup" -> "Manage Storage" -> "YeNom"___.

# Change Log

__v2.2.x @ Dev__

  - ...

__v2.1.5 @ Review__

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

Please email your comments, suggestions and questions to `dev#kjuly.com`.  
Or you can just post a bug report or a feature request [__HERE__](https://github.com/Kjuly/YeNom/issues/new).

Thank you! :)

