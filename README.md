# README #

### What is this repository for? ###

This project is a research application of a rigid object scanner by using the Microsoft's Kinect.

### How do I get set up? ###

This project is built on Visual Studio 2012.
There are two additonal libraries need to be initialized.

1. OpenCV 2.4.9 must be initialised and $(OPENCV_DIR) must be added under the sytem paths.
2. Point Cloud library 1.7.2 for VS2012. http://unanancyowen.com/?p=1255&lang=en
    1. PCL 1.7.2 can be found under project's Download section. Here is the guide to install it properly.
        1. Download the All-in-one Installer, and install. In the standard, PCL is installed in the “C:\Program Files\PCL 1.7.2″ (or “C:\Program Files (x86)\PCL 1.7.2″). Please use the Uninstall.exe when you want to uninstall.
        2. Set the environment variable for PCL and 3rdParty.
            1. PCL_ROOT	C:\Program Files\PCL 1.7.2(or C:\Program Files (x86)\PCL 1.7.2)
            2. Path	;%PCL_ROOT%\bin  ;%PCL_ROOT%\3rdParty\FLANN\bin  ;%PCL_ROOT%\3rdParty\VTK\bin
            3. If you installed the OpenNI2, as well setting the following path.
            4. Path	;%OPENNI2_REDIST64%(or %OPENNI2_REDIST%)

You can start to test by PlayGound class with the testData under testData directory.