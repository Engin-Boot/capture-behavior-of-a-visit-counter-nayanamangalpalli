# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

Given a system consists of sensor that counts number of patients and display\
And: system working 24/7\
When patient enters the hospital\
Then the patient count is incremented\
And:shown on display
<hr>
Scenario: Compute parking slots to reserve for visiting specialists

Given a system that manages schedule of specialists\
And: limited space\
And: security staff available

When vehicles of visiting specialists enters a hospital\
Then the allocated parking slot number is given to specialist\
