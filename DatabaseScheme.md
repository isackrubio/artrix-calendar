# Database Scheme #

### calendar: individual calendars belong to each user ###
|_Field_|_Type_|_Null?_|_Default_|_Description_|
|:------|:-----|:------|:--------|:------------|
|**calendar\_id**|int(6)|No     |         |Calendar ID  |
|**calendar\_name**	|varchar(150)	|No	    |General Events|Calendar Title|
|**calendar\_description**	|varchar(250)	|Yes	   |NULL	    |Calendar Description|
|**sharing**	|tinyint(4)	|No	    |0	       |It is enabled sharing to other user and outside? {1,0}|
|**adjustable**	|char(1)	|No	    |0	       |Enable to be modified by other users {1,0}|
|**color**	|varchar(6)|Yes    |ee8800   |Event display color|
|**user\_id**|int(20)|No     |         |Onwer User ID|

### calendar\_sharing: individual calendars whether from outside system or public URL location file belong to each user ###

|_Field_|_Type_|_Null?_|_Default_|_Description_|
|:------|:-----|:------|:--------|:------------|
|calendar\_id	|int(6)	|No	    |	        |Calendar ID  |
|url	   |varchar(255)	|Yes	   |	        |URL or file location|
|title	 |varchar(150)	|No	    |General Events	|Calendar Title|
|show	  |tinyint(4)	|No	    |1	       |Display calendar on scheduler ?{0,1}|
|color	 |varchar(6)	|Yes	   |ee8800	  |Event display color|
|user\_id	|int(20)	|No	    |	        |Created User ID|
|calendar\_id\_shared	|int(20)	|Yes	   |NULL	    |Onwer User ID|

### events: table of event detail in each individual calendar ###
|_Field_|_Type_|_Null?_|_Default_|_Description_|
|:------|:-----|:------|:--------|:------------|
|event\_id	|int(11)	|No	    |	        |Event ID     |
|event\_name	|varchar(127)	|No	    |	        |Event Title  |
|start\_date	|datetime	|No	    |	        |Start Date and Time|
|end\_date	|datetime	|No	    |	        |End Date and Time|
|details	|text	 |No	    |	        |Description  |
|calendar\_id	|int(6)	|Yes	   |NULL	    |Calendar ID  |

### settings: table of setting value which are defined by each user ###
|_Field_|_Type_|_Null?_|_Default_|_Description_|
|:------|:-----|:------|:--------|:------------|
|user\_id	|int(20)	|No	    |	        |User ID      |
|settings\_id	|varchar(15)	|No	    |	        |Settings Name|
|value	varchar(20)	|Yes	  |NULL	  |         |Value        |

### support: table of recording the feedback from users ###
|_Field_|_Type_|_Null?_|_Default_|_Description_|
|:------|:-----|:------|:--------|:------------|
|support\_id	|int(12)	|No	    |         |	Support ID  |
|notice	|text	 |No	    |	        |Title        |
|detail	|text	 |No	    |	        |Detail       |
|user\_id	|var(150)	|No	    |         |	Reported User ID|
|date	  |timestamp	|No	    |CURRENT\_TIMESTAMP	|Recorded Date|
|IP	    |varchar(30)	|Yes	   |NULL	    |User IP      |
|user\_agent	|varchar(200)	|Yes	   |NULL	    |User Agent   |
|status	|char(1)	|No	    |0	       |Status {0,1,2}|
