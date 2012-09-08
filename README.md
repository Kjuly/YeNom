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

__v1.8.x @ Dev__

  - ...

__v1.7.11 @ Review__

  - Change navigation bar style for mail view;
  - Allow to enter 'Free Code' to turn 'Full Features' on;
  - Modify default keyboard style for tag adding;
  - Fix record tag's frame width;
  - Enable purchase for 'Full Features';
  - Fix navigation bar back button's state: back to previous view from donate view when loading timeout;
  - Modify options (Fast, Normal, Slow) for delay time setting;
  - Offer an action sheet to user for confirming to delete the tag;
  - Reset selected cell index after remove the tag item;
  - Optimize performance;
  - Change icon;
  - Add basic calculation function for number pad;
  - Change system keyboard to customize keyboard for number pad.

__v1.6.8 @ 2012-08-23__

  - Fix bug: Selecting a row in one section leads the same row of another section to expand either;
  - Fix bug for statistics: Double count for 00:00 and 24:00;
  - Fix bug: Delete the data at 00:00 of next month incorrectly while deleting one month's data;
  - Allow user to delete all records for one month; 
  - Rename "Delay Time for Swipe Gesture" to "Delay TIme" in settings view;
  - Optimize performance;
  - Support year setting in statistics view;
  - Modify statistics view: support month & day statistics.

__v1.5.4 @ 2012-08-23__

  - Allow user to toggle iCloud service;
  - Add iCloud;
  - Enable to delete a single record.

__v1.4.3 @ 2012-08-09__

  - Add some help views for gestures;
  - Fix a bug: Adding the first record leads the font size to be wrong;
  - Remove `+` / `-` button in the root view, use drag-and-hold gesture only;
  - Part UI modified;
  - Add In-App Purchase for donation.

__v1.2.4 @ 2012-07-26__

  - The first released version on App Store.

# Feedback

Please email your comments, suggestions and questions to `dev#kjuly.com`.  
Or you can just post a bug report or a feature request [__HERE__](https://github.com/Kjuly/YeNom/issues/new).

Thank you! :)

