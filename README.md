## PHP Based File Manager Application
### Installation
Clone or download simple-file-manager.zip file and extract file in your server.
After extraction go to simple-file-manager folder and open your cmd (comand prompt) , run the following commands in cmd (comand prompt). 
    
    php composer dump-autoload -o
    
### Application Test Case
**Title:** Add File
**Description:** An User should be able to add file.
**Precondition:** The user can upload only allowed file format. By default user can upload any kind of file format except .php and .html extension.
**Assumption:** A supported browser is being used.
**Test Steps:**
- Navigate to {your host}/simple-file-manager
- In the right top corner you can see Add File button
- Click the button and drop or browse your file to add.

**Title:** Create Folder
**Description:** An User should be able to create folder.
**Precondition:** Creating folder name should be valid text format, avoid special character in your folder name.
**Assumption:** A supported browser is being used.
**Test Steps:**
- Navigate to {your host}/simple-file-manager
- In the right top corner you can see Create Folder button
- Click the button and enter valid folder name.

**Title:** Download/Delete/Rename File and Folder.
**Description:** An User should be able to download/delete/rename file and folder.
**Precondition:** Rename folder name should be valid text format, avoid special character in your folder name.
**Assumption:** A supported browser is being used.
**Test Steps:**
- Navigate to {your host}/simple-file-manager
- Right click on your file and folder.
- A small popup open. 
- Then choose your option to download/delete/rename and click the button.
- To renaming folder or file name enter valid name.

**Title:** Setting or Configure your file manager.
**Description:** An User should be able to allow/disallow add file, create folder, download file, direct download link and set max upload size.
**Precondition:** To configure file manager you need to login admin panel using a valid username and password.
**Assumption:** A supported browser is being used.
**Test Steps:**
-  Navigate to {your host}/simple-file-manager
- In the right top corner you can see Setting link
- Click the link or enter direct url of admin panel ({your host}/simple-file-manager/admin).
- A default username and password is **username:** admin, **password:** admin.
- Click login button.
- After successfully logged in admin panel, you can see all configure option.
- Update your configure option and click on save button to applying updated configuration.

`[N.B: Copy and Move Not Working Currently]`


