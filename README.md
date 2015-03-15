# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
This project is a research application of a rigid object scanner by using the Microsoft's Kinect.

### How do I get set up? ###

* Summary of set up
This project is built on Visual Studio 2012. 
Firstly There are two additonal libraries need to be initialized.
- OpenCV 2.4.9 must be initialised and $(OPENCV_DIR) must be added under the sytem paths.
- Point Cloud library 1.7.2 for VS2012. http://unanancyowen.com/?p=1255&lang=en
  PCL 1.7.2 can be found under project's Download section.
  Here is the guide to install it properyly
  Install and Setting Environmental Variables, and Setting Project

  Download the All-in-one Installer, and install.
  
  In the standard, PCL is installed in the “C:\Program Files\PCL 1.7.2″ (or “C:\Program Files (x86)\PCL 1.7.2″).
  
  Please use the Uninstall.exe when you want to uninstall.



  Set the environment variable for PCL and 3rdParty.


  PCL_ROOT	C:\Program Files\PCL 1.7.2(or C:\Program Files (x86)\PCL 1.7.2)
  
  Path	;%PCL_ROOT%\bin  ;%PCL_ROOT%\3rdParty\FLANN\bin  ;%PCL_ROOT%\3rdParty\VTK\bin
  
  
  
  If you installed the OpenNI2, as well setting the following path.


  Path	;%OPENNI2_REDIST64%(or %OPENNI2_REDIST%)

You can start to test by PlayGound class with the testData under testData directory.