# File Descriptions #

Another way to help the developer understanding how the system works overall, there are the descriptions of programming file in the calendar system as shown the table:

|_Folders / Files_|_Actions_|
|:----------------|:|
|_(root)_         |_Main Folder_|
|.htacess         |- Manage accessing files|
|index.php        |- Login, sign up page and announcement list|
|chkserver.php    |- Check the system that can still able to communication or on the internet connection via Ajax of DHTMLX|
|main.php         |- Main page of system|
|main\_script.js  |- The main page javascript acts on several funtiontions of DHTMLX |
|signout.php	     |- Sign out page and then redirect page to index.php|

|_codebase_|dhtmlxScheduler folder|
|:---------|:---------------------|
|->connector|- A set of file is managing the database connection|
|->ext     |- A set of file is the extension of dhtmlxScheduler|
|->imgs    |- A set of file is concerning the dhtmlxScheduler layout|
|dhtmlxscheduler.css|- CSS file of dhtmlxScheduler definition|
|dhtmlxscheduler.js|- Main javascript of dhtmlxScheduler|
|dhtmlxscheduler\_debug.js|- Main javascript file of dhtmlxScheduler but it can show the error or warning during running the system (released system does not call this file)|

|common|Generic file container|
|:-----|:---------------------|
|--> css|- CSS files           |
|    .htaccess|- Command set of accessing file|
|    css\_event.php|- Configurable Color set |
|    style.css|- Scheduler style page|
|--> icon|- Icon files          |
|--> image|- Image files         |

|component|Third Party library folder|
|:--------|:-------------------------|
|--> dhtmlx| - All DHTMLX module files|
|--> imgs |- DHTMLX image files in each its module|
|    dhtmlx.css|- CSS file of DHTMLx, every module is compiled|
|    dhtmlx.js|- Javascript file of DHTMLx, every module is compiled |
|    mainifest.txt    |- Log file from DHTMLx    |
|extension.js|- Calling extension file  |
|iCalcreator.clsss.php|- iCal external class     |
|mysql\_module.php|- Main MySQL connection management file|

|event|Event Management files (XML format)|
|:----|:----------------------------------|
|events.php|- Manage the event from user (Show data/Add/Edit/Delete)|
|events\_internal.php|- List of the internal calendar in system (Only enable)|
|events\_search.php|- Search the event data from calendar table|
|events\_share.php|- Retrive the event from calendar table to export as HTML|


|frame|iFrame files|
|:----|:-----------|
|calendar\_image.png|- Image of calendar|
|calendar\_settings.php|- Own calendar setting page|
|internal\_settings.php|- Other-user internal calendar setting page|
|render.php|- Show the scheduler frame|
|shared\_settings.php|- Public or outsource calendar setting page|
|support.php|- Feedback form received by current user|
|system\_settings.php|- Profile and system user setting page|

|help|Support/Help folder|
|:---|:------------------|
|-> images|- Support image files|
|new.php|- The iframe page shows the announcement messages from administrtors|

|share|Sharing Management files|
|:----|:-----------------------|
|.htacess|- Manage Accessing file xml, html, ical on URL|
|buffer.php|- Cache file management |
|html.php|- Render the calendar table (dhtmlxSchedule) |
|ical.php|- Export the event in format of .ics to use outside the system that allow other to select/add/edit/delete|
|ical\_put.php|- Receive file iCal from input of client program such as Thunderbird|
|ical\_select.php|- Import the event from public URL or oursource|
|shared\_internal.php|- Show the internal calendar list that using in the selective table in format XML |
|xml.php|- Export event drumping into .xml format to use outside the system|

|admin|Administration Management site|
|:----|:-----------------------------|
|-> SpryAssets|- Display CSS component       |
|index.php|- Mainpage of administration site|









