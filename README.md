# Omnis-CreateForms
A simple app to create multiple blank forms at construct and delete them at destruct. 

Requires Omnis Studio 8.1.2 or above

## Contents
### CREATEFORM
This folder contains the source JSON files for the Omnis library in Github. 

To restore these files in Omnis Studio, click on the Libraries option in the Studio Browser, and click on the New Lib from JSON option. In the New Library (import) dialog, navigate to this source folder (containing library.json), and then specify a different folder or location for the new Library. Click on Import and open the library in the Studio Browser. 

After importing the library open the Startup_Task to create the window classes (right-click on Startup_Task and select Open Task), and close the Startup_task (Right-click >> Close Task) to remove them; closing the library will also close the task and remove the classes. Examine the code in the Startup_Task class.
