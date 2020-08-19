# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

Given a system consists of sensor that counts number of visitors and backend server

When a sensor counts number of visitors

Then server provides a report of number of patients visiting hospital\
on hourly and daily basis.\
(Patients mostly come at evening or saturday,sunday)

Scenario: Alert when seating capacity is full

Given a limited number of seats are available\
And: system consists of sensor which counts empty seats and backend server

When only two empty seats are remaining.

Then notification sent to facility manager that\
seating capacity will be full in while.
