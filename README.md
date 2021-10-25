# Mock interview scheduler

## Requirements
* __Goal__: To allow experienced developers who loves to give mock interviews and developers who wants to better at interviews to discover each other.


## Functional requirements

Feature | User story | Requirement | Priority
--------|------------|-------------|---------
Register [Interviewer]| The user should be able register. | The system must allow the user to register using email or phone number along with a link to their linked in profile. | Must have
Login [Interviewer]| The user should be able login into their account. | The system must allow the user to login using email or phone number, and password. | Must have
Setup schedule [Interviewer]| The user should be able set up a schedule accoring to their convinience.| The system should allow the user to add recurring time slots that the user is free to give mock interviews. The user should be able to choose repeat by week of the day, calendar date etc..| Must have
Choose topic [Interviewer] | The user should be able to choose a list of topics that they wish to give interviews on. | The system should allow the user to choose from among a list of topics to add to their profile. The user should be able to add a new topic if the topic that they are interested is not in the list. | Must have
See scheduled interviews [Interviewer]| The user should be able to see the list of interviews assigned to them. | The system should allow the user to list all the upcoming and previous interviews in a tidy view.| Must have
Receive calendar invite [Interviewer]| The user should be able get a calendar invite automatically. | The system should automatically send a calendar invite to the user the when an interview has been assigned to them. | Must have
Get notification [Interviewer] | The user should get a SMS or email notification when an interview is assigned to them | The system should send an automated SMS or email to the user when an interview has been assigned to them. | Nice to have
Cancel a slot [Interviewer] | The user should be able cancel an upcoming slot. | The system should allow the user to mark an upcoming timeslot as busy so no interview is assigned to them | Nice to have
Cancel an interview [Interviewer] | The user should be able to cancel an interview assigned to them. | The system should allow the user to cancel an interview that has already been assigned to them. | Nice to have
Logout [Interviewer]| The user should be able logout from their account. | The system must allow the user to logout of their account. | Must have
Register [Candidate]| The user should be able register. | The system must allow the user to register using email or phone number along with a link to their linked in profile. | Must have
Login [Candidate]| The use should ne able to login to their account. | The system must allow the user to login using email or phone number, and password. | Must have
Request Interview [Candiate] | The user should be able to request a mock interview on a topic of their choosing, at a time of their convinience. | The system should allow the user to choose a topic from a list of available topics and choose a date and time slot and send an interview request. | Must have
Receive calendar invite [Candiate]| The user should be able get a calendar invite automatically. | The system should automatically send a calendar invite to the user the when the user's interview request has been approved. | Must have
Get notification [Candiate] | The user should get a SMS or email notification when an interview is assigned to them | The system should send an automated SMS or email to the user when their interview request has been approved.| Nice to have
Logout [Candiate]| The user should be able logut into their account. | The system must allow the user to logout from their account. | Must have
Login [Admin]| The user should be able login into their account. | The system must allow the user to login using email or phone number, and password. | Must have
See interviewer registrations [Admin] | The user should be able to see all the pending registration requests. | The system should list all the registration requests along with a link to their linked in profile. | Must have
Accept registration [Admin] | The user should be able accept a registration. | The system should allow the user to mark a registration request as approved. | Must have.
Reject registration [Admin] | The user should be able to reject a registration. | The system should allow the user to mark a registration request as rejected. | Must have.
See interviewers schedule [Admin] | The user shoule be able to see the schedule and topics of an interviewer. | The system should allow the user to see the available slots of an interviewer that they choose. The system should list current and upcoming slots, along with their topics in a tidy view.| Must have
See available interviwers [Admin] | The user should be able to see available interviewers for topic on a specified date. | The system should allow the user to choose a topic and a date and the system should list all the available interviewrs on availble on that date for that topic. | Must have
See interview requests [Admin] | The user should be able see a list of interview requests. | The system should list all the interview requests along with the preferred timeslots and required topic. | Must have
Assign interview [Admin] | The user should be able assign an interview request to an interviewer. | The system should allow the user to assign an interview request to an interviewer. The system should mark the slot as occupied and notify the parties. | Must have
Re-Assign interview [Admin] | The user should be able re-assign an interview request from one interviewer to another. | The system should allow the user to assign an interview request from one interviewer to another. The system should mark the slot as new slot as occupied and notify the parties. | Nice to have
Logout [Admin]| The user should be able logut into their account. | The system must allow the user to logout from their account. | Must have


