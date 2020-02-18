# EMS

Event Management System (EMS) 
Over all Description.

As of its title (EMS) has been prepared to manage students requests for joining some events.
Student first should provide some of his/her info to be able to register through the system
First of all "Home" Interface appears in order to choose between (Admin role | and Student role) for the first step for user in side system 
(Note: all interface are still available to visit regard less of first choice, as there is no login module for the system to distinguish between roles)

For student role, Student submit his own info using this form before navigating through the system and choosing an event to register for. 
 
Some Fields of this form is mandatory, and it should follow a specific criteria, so when avoiding that, the registration form notify the student about these data like below

When student enter his data in a correct way, submission button appears to submit this data
 
After successful submission, system automatically takes the student to the events page
In order to choose one or more to register with
 
All Events are available for student to register until he takes the decision to go for one or more of them, once registration request submitted successfully, then and in the same event card, registration button disappears, and (pending) request status appears instead, to let student check his registration requests' status for each event in the same page immediately.
 
[for above sample student choose the first three events to attend, so request status appeared for them, while other two events are still available for registration]
Once requests sent -and from admin perspective - three new requests appears in registration requests table, with its current status(pending), in order to take an action for each.
 Approve and reject actions are available in line for admin to take for each request,
Where request status updated immediately if (Approve/Reject) request processed successfully.
 
[above screenshot demonstrate that's admin approved the first request and reject the second one, where the third one left pending]
When action takes place, request's new status reflected as well to events interface for student in order to check
  [New requests' status on event's page]
Admin my wish to check student info before taking action, so admin can move to students list interface and filter by student name in order to check his info
[features of filtering – sorting are all available for all fields in students' Interface in addition to pagination] 
As following
 
 
Regarding student's data, We can develop many statistics based on, and some of them were applied inside the dashboard interface as following :
1.	Distribution of students' gender
For all of system students the percentage of Male Vs. Female 
2.	Distribution of students' Ages
For all of system students the percentage of each available age for students to overall count of students ages
The following part of dashboard interface demonstrate above statistics
 
In addition to above, system provides another two types of statistics
3.	Distribution of student's per universities
For all of system students the number of students belong to each of student's universities(i.e. 3 students  MIT , 6 Stanford, …)
4.	Distribution of students' requests per system events
And for information purposes about events, system provides the number of requests sent by students for each of system events
The following part of dashboard interface demonstrate (3 and 4) statistics
 

In addition to above statistics we may go further and provide more statistics like:
•	Distribution of student's [Gender | Age | University] per one specific event
or per all system events ,i.e.:
o	Percentage of male students requested to join (Welcome Event) comparing to percentage of female students requested to join it.		 
o	Distribution of student's ages who requested to join (CS Event).
•	Number of [Approved | Rejected | Pending] requests per specific event or per all system events.
•	Distribution of student's [Gender | Age | University] per [Approved | Rejected | Pending] for specific event or for all system events, i.e.
o	3 approved requests for male, and 4 approved requests for female
regarding (Telecomm Event) etc…


Thanks for reading.
-------------------------------------------
