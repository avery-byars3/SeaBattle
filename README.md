# StudentRegSystem
This application was created as personal practice in Java. The program simulates a student registration system, like one that most people who have gone or are currently going to college have used.
#### The program allows the user to:
* Search for specific courses in the database by a course number, and the database will return a list of classes available.
* Register for a specific class by entering the corresponding CRN number (the system will not allow a class to be registered for if it has a time confliction with another class).
* View a trial schedule in the form of a list of the courses that have been added to the schedule so far.

Each of these are chosen from a simple menu upon opening the program.

## Prerequisites
* Java Development Kit (JDK)
* Netbeans IDE

## Installing
### Installing JDK:
http://adoptopenjdk.net/releases.html (Links to an external site.)

This is a direct link to the official Java SE download page from the AdoptOpenJDK projct; it includes a link to Java 8, the version of Java that we are currently using in the lab.

When you are ready to install Java on your personal computer, open this link, select the most recent version of Java 8 if it is not selected already, and be sure to select the correct platform. For example, if you are running a 64-bit version of Windows (which you probably are if you have a fairly recent computer), click the "Windows x64" link to download the 64-bit installer. If you have a 32-bit computer, download the "Windows x86" version instead.

NOTE: During the installation, be sure that the "Set JAVA_HOME Variable" feature is enabled in the "Custom Setup" screen; to do this, click the drop-down list of options next to this feature and choose "Will be installed on local hard drive." If you have already completed the installation, and if you subsequently have trouble getting NetBeans and other Java applications to find your JDK, see the note in the "NetBeans IDE" section below to set this variable manually.

### Installing Netbeans IDE
http://netbeans.org/downloads/8.2 (Links to an external site.)

This is a direct link to the official NetBeans 8.2 download page, which is the version of NetBeans that we are currently using in the lab. Before installing NetBeans, make sure you have Java 8 installed (this version of NetBeans does not officially support Java 9 or above).

When you are ready to install NetBeans on your own computer, open this link. In the "Platform" selector (in the upper-right corner of the page), select your operating system platform; for example, "Windows" if your computer runs Microsoft Windows. Then, at the bottom of the "Download Bundles" table, click the "Download" button corresponding to your version of Java. The "Java SE" version is sufficient, though you can also install the "Java EE" version of NetBeans (this version adds Web application functionality that you might find useful in your future classes).

NOTE: Sometimes, the NetBeans installer will report that it cannot find an installed JDK on your workstation, even though you may have completed the OpenJDK installation. This usually means that the "Set JAVA_HOME Variable" feature, which helps Java applications find your installation of Java, was not enabled when OpenJDK was installed. Fortunately, it is not difficult to set this variable manually. If you are using Windows:

Open the File Explorer, then right-click "This PC" in the list of locations on the left, and choose "Properties." The "System" window should appear, showing information about your version of Windows. Click the "Advanced system settings" link on the left to open the "System Properties" window; in the "Advanced" tab of this window, click the "Environment Variables" button. Yet another window will open, showing a list of environment variables at the top and system variables at the bottom. You should see a "New..." button near the bottom of this window; click this button, and when prompted, enter "JAVA_HOME" as the variable name and "C:\Program Files\AdoptOpenJDK\jdk-8.0.222.10-hotspot" as the variable value. Enter both without the double-quotes. (Note that this is the version of OpenJDK that is currently in use in the lab. Your version number may be slightly different, so you should click "Browse Directory" and then browse the filesystem on your "C:" drive to find the installation folder under "C:\Program Files\AdoptOpenJDK"; if the folder name is different, use it instead.) Click "OK" in each of the open windows to commit your changes, and after they have all been closed, try the OpenJDK installation again.

### Authors
* Avery Byars
