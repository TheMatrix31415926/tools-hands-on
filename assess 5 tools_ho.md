# &#x20;Voice Call Automation Flow (Bolna.ai)

## &#x20;Use Case: Appointment Reminder Call



## &#x20;Conversation Flow



**Step 1: Greeting \& Identity Confirmation**



Purpose: Ensure the agent is speaking to the correct person



AI Message:

"Hello, this is an automated call from ABC Clinic. May I please speak with {Customer Name}?"



Expected Response:

Yes

No

Asking who is calling



Captured Data:

Confirmation if the correct person is on the call



**Step 2: Inform Purpose**



Purpose: Explain the reason for the call and check availability 



AI Message:

"We are calling to remind you about your appointment scheduled on {Date} at {Time}. Is this a good time to talk?"



Expected Response:

Yes

No



Captured Data: User availability to continue the conversation



**Step 3: Appointment Action**



Purpose: Understand user intent regarding the appointment  



AI Message:

"Would you like to confirm, reschedule, or cancel your appointment?"



Expected Response:

Confirm

Reschedule

Cancel



Captured Data: Appointment status (Confirmed / Rescheduled / Cancelled)



**Step 4: Capture Details**



Purpose: Collect additional information based on user choice



AI Message:



If Confirm: "Great! We look forward to seeing you."



If Reschedule:

"Please tell us your preferred date and time for rescheduling."

If Cancel:

"May I know the reason for cancellation?"



Expected Response:

New date and time (if rescheduling)

Reason for cancellation (if cancelling)



Captured Data: New appointment schedule OR Cancellation reason



**Step 5: Closing**



Purpose: End the call politely and clearly



AI Message:

"Thank you for your time. If you need further assistance, please call us back. Have a great day!"



Expected Response: Optional acknowledgment



Captured Data: Call completion status 



## &#x20;Information Captured

* Customer identity confirmation
* Availability to talk
* Appointment status (Confirmed / Rescheduled / Cancelled)
* New appointment date \& time (if rescheduled)
* Cancellation reason (if cancelled)



## &#x20;Fallback / Escalation

* If user response is unclear or no response detected:  
"I'm sorry, I didn’t catch that. Let me connect you to a human agent for further assistance."
* Action: Transfer call to human agent or schedule a callback.



## &#x20;Outcome

This flow ensures:

* Polite and clear interaction
* Efficient data capture
* Smooth handling of different user responses
* Clear closure or escalation when needed

