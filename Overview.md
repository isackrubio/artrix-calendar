# System Overview #
## Program Components ##

 We deployed the 3rd party component storing in the folder of “codebase” and “component”

![http://artrix-calendar.googlecode.com/svn/wiki/screenshot_main.jpg](http://artrix-calendar.googlecode.com/svn/wiki/screenshot_main.jpg)
_Figure 1 Main page_


List of component open source (GPL/GNU License) as following:

**DHTMLX eXtensions**: www.dhtmlx.com (By Saint-Petersburg Company, Russia) Professional  AJAX components for advanced Web UI.
It operates with its each module and works well compatibility. There are modules such as:

  * dhtmlxScheduler: acts on whole scheduler process and the GUI part of event which has other plug-in extra components
  * dhtmlxAccordion is part of the accordion in GUI
  * dhtmlxGrid  is part of the grid list in GUI which shows the result of searching calendar list
  * dhtmlxLayout is part of the window layout in GUI which can be defined with 3 divisions (3W) as left, center and right panel
  * dhtmlxMenu acts as the menu part
  * dhtmlxToolbar acts as the toolbar
  * dhtmlxWindows acts as all windows popups
  * dhtmlxDataProcessor processes and controls the database via the grid and scheduler as well as it can record debugging into the log file
  * dhtmlxCalendar is the GUI  showing mini selective calendar in the left-hand side

**DHTML Goodies**: www.dhtmlgoodies.com is the code of hint or help message showing on the small panel of the bottom

**iCalcreator class v2.4.3**: www.kigkonsult.se/iCalcreator/index.php manages files involved the iCalendar (.ics) entirely

**My SQL Module**: assists the system communicating with MySQL database system as the class object
#PHPMailer (Version: 2.0.0 rc3) http://phpmailer.worxware.com/index.php?pg=phpmailer    is the class object which email user the message via PHP SMTP

## System requirements ##
  * Apache Ver.2 or higher
  * PHP Version 4.3.0 or higher
  * MySQL Version 4.0 or higher