## User Story

As a patient, I want to reschedule my appointment within 24 hours of window, to update my appointment less than hours before the original time scheduled.
 
## Acceptance Criteria (Given / When / Then)

SENARIO: Patient reschedules an appointment with 24 hours
 
Given a patient has scheduled appointment 2026-10-15T10:00:00Z
 
When the patient requests a reschedule to less than hours before the original time  "2026-10-16T14:00:00Z" less than hours before the original time 

 
##Tasks

-[ ] Take the users input
-[ ] Check if the input is valid 
-[ ] Retrieve date from database
-[ ] Compare input with the database 
-[ ] Apply a late- change flag 
-[ ] Update the details in the data base    
-[ ] Emit  'AppointmentRescheduled' event 
-[ ] Send the event to notification service 
-[ ] Send Appointment details back to Appointment system 
-[ ] Display a confirmation message to patient 
-[ ] Display updated appointment details 
-[ ] Write automated tests for the rescheduling scenario 

  
  
