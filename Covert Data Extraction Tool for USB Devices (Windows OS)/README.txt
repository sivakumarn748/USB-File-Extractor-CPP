This application works only on 64-bit Windows OS.



Instructions:
------------

1) Set the removable drive label in the "driverlabel.txt" file.
   Example: Just put "G" in the file. Do not use "G:" or "G:\".

2) Set the target location in the "Location.txt" file.
   Example: Use a full directory path like "G:\Folder\targetfolder\".
   Do not use relative paths like "./folder".

3) Run the "system-x64.exe" file.

4) Wait for the drive to be inserted.
   The time taken for copying depends on the folder's size and depth.

5) Copied folders will be found in the "Saved" folder.
   This folder is created automatically — you do not need to create it manually.



Stopping the Application:
------------------------

Use Task Manager to end the "system-x64" process to stop the application.



NOTE:
----

- The label of the removable drive must be known and must match the label in "driverlabel.txt".
- The application can also be set to run automatically at startup by placing a shortcut to "system-x64.exe" in:
  C:\Users\<YourUsername>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
