Grizzly Roulette
ITEC 4550 Flutter Project

        

        

Description

Create a flutter application that picks a random student name. Tapping the floating action button will initiate a random selection and present the result at the top of the screen. Tapping on a list item will toggle its state between hidden and visible. Hidden items are displayed with the Icons.visibility_off icon, as illustrated above. Visible items are displayed as text only, no icon is present.  When items are hidden, those items are not available for random selection. Swiping an element to the left will remove it from the list. 

The Settings (three dots in upper righthand corner) menu should contain options for: Settings …, OCR …, and About.

The icon graphic for the FloatingActionButton must be changed from the default setting to use the Icons.sync graphic. 

The launcher icon should be redefined to use twentydiegreen.png. 

The student list should be persisted across application restarts. 
Several resources are listed at the end of this description that should help, if you need more information. A demonstration video can be viewed here.

Requirements/Rubric:
All items below are graded on an ‘all or nothing’ basis. For example, If you omit the Clear option under the list maintenance drawer, 2 points will be deducted.
Your application must:
2 - Contain an About screen with the building header graphic, ITEC 4550 as text, an image of your choosing, the date you created the app, and your name (or teammates’ names). Navigation back to the main screen must be provided.
2 - Options menu (aka Settings) contains: Settings …, OCR …, and About.  The left side drawer contains options to Add Name, Sort, Shuffle and Clear the list. All list operations must function properly. Settings… and OCR … are not completely operational yet, simply display a SnackBar noting that 'Settings (/OCR) will be coming soon'.
2 - Selecting Add Name from Settings redirects to another route (aka page) and allows the user to type a new name, accept with ‘Add’ button or cancel with an X or <- button. The student list is updated accordingly.
2 - Swiping an element to the left removes it from the underlying list and the ListView.
2 - The current list of names is persisted upon app shutdown and restored upon app start. Hidden/visible states must be persisted, as well.
2 – In the list, display hidden items with the Icons.visibility_off Icon, visible items without any icon. Toggling a list item’s visibility with a tap reverses the hidden setting. Provide an informational message if a user tries to pick a random name when all names are hidden or the list is empty.
2 – Launcher icon has been replaced by the provided twentydiegreen.png graphic.
2 – Image bbuildingwavy.jpg appears at the top of the main app screen below the AppBar, as shown above. Titles appear as illustrated in the screen shots, above.
2 – Show a list of names using ListView with ListTile widgets. Tapping the FAB results in a new, random item being displayed. Floating Action Button (FAB) contains Icons.sync Icon. Random selections with the FAB tap will never select a hidden item. 
2 – include author information, course number and date within the About page. Implement a logging strategy. Print random selection results to the logcat (/console) each time the FAB is pressed.
Notes
-Reference files are posted to Week 13 folder in course OneDrive. Note that you will need to update your project pubspec file with a reference to path_provider. More details at https://pub.dev/packages/path_provider.
-You may refer to my reference files and code samples that are provided
-You can build for and demo with Android or iOS – your choice
-You do not need to handle configuration changes such as device rotations. 
-You do not need to provide portrait and landscape layouts, one will suffice.
-You do not need to plan for multiple image resolutions for multiple device size. Building and demoing on one device or emulator is sufficient.
-Export the zip directly from Android Studio with File -> Manage IDE Stettings -> Export to Zip File (or File -> Manage IDE Settings -> Export to Zip File, depending on your version of Android Studio). I must be able to recreate your project from this zip.
-Remember to design your app such that you could demonstrate in a future interview scenario! What seems funny or edgy now could not play well in an interview/demo.
Hints / Resources

-Don’t forget the course’s “Help!” forum
-I started with this example: https://flutter.io/cookbook/lists/mixed-list. I then merged with the structure in flutter’s hellow_world app to get the functionality.
-There are a lot of great examples in the flutter_gallery. You can find instructions on github and the examples are already on your system.
-Notes on flutter’s asset management are here: https://flutter.io/assets-and-images.
-I followed/modified:
https://insertbreakpoint.wordpress.com/2018/03/28/flutter-list-dialog-example
https://flutter.io/docs/cookbook/persistence/reading-writing-files
https://pub.dartlang.org/packages/flutter_launcher_icons 
-For pausing / resuming:
https://dev.to/pedromassango/onresume-and-onpause-for-widgets-on-flutter-27k2
https://github.com/pedromassango/flutter_app_lifecycle/blob/master/lib/main.dart
-Sometimes, hot reload doesn’t work as intended. If you experience this, try stop/starting the app.
Submission
-You must submit your final android studio project as a zip folder in the D2L dropbox
-Provide a link to your project page. The Via project page must contain a link to your demo video
-In your video, demonstrate all your app’s features, highlighting each requirement above. If the demonstration fails to illustrate the requirement, you will not receive credit
-Your project page should follow the standard course template for assignments. Do not share your solution source on your project page. 
-Submissions missing a project wiki page or video will receive a zero.
-You must present your solution to the class during our last class (Jun 16th) or the final exam period (Jun 17th), or you will receive a zero.
-If you work on a team, every team member must make a submission of the project zip to the D2L dropbox. Teams nust be declared by 11:59 pm Minday Jun 14th. Additionally, provide the link to your team project page. Only one project page and one video is required for each team. Upon submission, provide a statement of each team member’s contribution, working with a budget of 100%. For example if John, Will and Jean each contributed about the same, but Jean did a little bit more, you could report Jean 40%, John 30% and Will 30%. Failure to submit a contribution statement will be subject to a deduction.
