C# samples for The Eye Tribe Tracker
====

Introduction
----

This is the C# samples repository for The Eye Tribe Tracker. The implementation provides examples of how to use eye gaze coordinates for simple UI interaction. Furthermore, it contains basic UI elements useful to give feedback to the user and run a calibration.

More samples will be added to the repository in the near future.

Please visit our [developer website](http://dev.theeyetribe.com) for more information.


TETControls
----

Provides example implementations of TrackBox and Calibration UI elements. These are employed in other samples.


Calibration
----

The calibration sample can be used to perform a user-based calibration on the system.


Scroll
----

The Scroll sample is a demonstration of how to employ natural scroll interaction while reading information-dense content (e.g., websites). Changing the information content is done with the mouse. A mouse-button down invokes a gaze-sensitive menu with selectable items and a mouse-up signals a selection to the application.


Dependencies
----

This sample uses the [EyeTribe C# SDK](https://github.com/EyeTribe/tet-csharp-client). 


Build
----

To build, open solution file in compliant [Visual Studio](http://www.visualstudio.com/) version and build.


Changelog
----

0.9.26 (2014-01-30)
- TETControls has been merged into this repository.
- The Utility class has been pruned
- Error states of the EyeTribe tracker is printed in the TrackBox
- TrackBoxHelper.cs has been integrated into the TrackBoxStatus.xaml  
- Minor UI tweaks 
- Improved scrolling function based on a Sigmoid
- A direction enum is used to determine the Scroll direction 

0.9.21 (2013-01-08)
- Initial release

