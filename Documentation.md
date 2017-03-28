# OPENCV2.1 INSTALLATION FOR WINDOWS SYSTEM USING DEV C++ EDITOR

# First Step :
Download OpenCV for windows.

Just go to the link below:
https://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.1/

You will find an exe file - "OpenCV-2.1.0-win32-vs2008.exe". Download and execute it by double clicking.
Once you are done with installing it, its time to add it to your C++ IDE.

# Second Step :
Here I'm illustrating how you can bind the openCV libraries to your Dev C++ IDE.

1. Open Dev C++ , Go to Tools -> Compiler options.

2. Click the green plus button just beside the "Compiler set to configure dropdown", and name it "OpeCV"(without quote)
Check the first checkbox, in the text area just below paste this line without quote - 
"-L"c:\opencv2.1\lib" -lcxcore210 -lcv210 -lcvaux210 -lhighgui210 -lml210"

3. Click on "Directories" nav below and import OpenCV2.1\bin folder.Add it.
4. Click on "Libraries" nav and import OpenCV2.1\lib folder. Add it.
5. Click on C includes nav and import OpenCV2.1/include/openCV.Add it.
6. Click on C++ includes nav and import OpenCV2.1/include/openCV.Add it.
    Click "OK" to finish compiler setting.

7. Create a project. Then go to  Project->Project options (or Alt + P).Go to the compiler nav and check wheather it is set to "OpenCV",if not ,set it to OpenCV.

Now you are good to go with OpenCV. Happy Coding :)


