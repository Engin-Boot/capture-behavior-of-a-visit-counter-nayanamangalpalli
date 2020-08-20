# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

Given a system consists of sensor that counts number of patients and display\
And: system working 24/7\
When patient enters the hospital\
Then the sensor increments patients count\
And:shown on display

Scenario: Compute parking slots to reserve for visiting specialists

Given a system that allocates parking slot to a specialist\
And: limited space\
And: security staff available

When vehicle of visiting specialists enters a hospital\
Then the staff gives a allocated parking slot number to a specialist.
