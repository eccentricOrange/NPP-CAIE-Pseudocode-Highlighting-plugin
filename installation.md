# Installation

## Downloading and installing Notepad++
1. Download Notepad++ from it's [official website](https://notepad-plus-plus.org/download/).
2. Install the software to your computer. Follow the instructions shown on the installer window. You might need administrator access to your computer system. Follow this [WikiHow tutorial](https://www.wikihow.com/Install-Notepad%2B%2B) for further assistance.

   Take note of the install location of the application. You may need this later.

3. Restart your system after installing the application

## Installing the Pseudocode Library
1. To download the ZIP folder that has the installation files, [click here](https://downgit.github.io/#/home?url=https://github.com/eccentricOrange/NPP-CAIE-Pseudocode-Highlighting-plugin/tree/master/npp-psu-plugin&rootDirectory=false). Extract the files.
2. Launch Notepad++
3. Click on the **Define your language** option under the **Language** menu. This should bring up a language editor window.
4. Click **Import...**
5. Locate the `Pseudocode Add-in.xml` file and click **Open**
6. You should get a pop-up informing you that the import was successful. Close it by clicking **OK**.
7. Close the language editor window using the ‘cross button’ on the top-right corner of the window.
8. Close the Notepad++ application
9. Navigate to the install folder of Notepad++. Go to `/autoCompletion` (create it if it doesn’t exist).
10. Copy and paste the `Pseudocode.xml` file in this folder. You may need administrator access to your computer system.
11. Restart the Notepad++ application
12. Click on the **Language** menu. If `PseudoCode` appears on the list, the add-on has successfully been imported.

## Change settings (optional)
Notepad++ ships with settings aimed at programmers and you might not be comfortable with these. Follow the steps below to change them, if that is the case.
1.	Launch Notepad++
2.	Click the **Preferences** option under the **Settings** menu. This should open a new window
3.	Under the **Editing** preferences set the L**ine wrap** option to `Aligned`
4.	Under the **Language** preferences set the **Tab Settings** so that the **Tab Size** is `4` and the **Replace by space** checkbox is checked 
5.	Under the **Print** preferences, make sure the **Print line number** checkbox is checked
6.	Click **Close** to exit.
7.	Restart the Notepad++ application

## Set Notepad++ as the default application for pseudocode files (optional)
Pseudocode files are saved with the file extension `.psu`. Since you are not likely to have another editor for pseudocode, it is recommended to set Notepad++ as the default application to use pseudocode files.
1.	Download the file `Pseudocode Syntax.psu` to your computer
2.	In File Explorer, select the file, right-click on it and click **Properties**
3.	Click the **Change** button
4.	You should see Notepad++ as an option; click on it. If not, follow these instructions
    * Click **More apps**
    * Scroll to the bottom and click **Look for another app on this PC**
    * Navigate to the install location of Notepad++
    * Open ``notepad++.exe``
5.	Click **Apply** followed by **OK**
6.	Open `Pseudocode Syntax.psu` by double-clicking it in the File Explorer. You should see a file similar to `Colouring Scheme and Syntax.pdf`.