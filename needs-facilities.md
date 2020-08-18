# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

Given a system working properly (counting and display of count)\

When a system provides a report of number of patients visiting hospital\
on hourly and daily basis.\
(Patients mostly come at evening or saturday,sunday)\

Then facility manager can arrange beds and seats based on report.

Scenario: Alert when seating capacity is full

Given the seating capacity is limited and alert system working properly.\

When alert system is offline\

Then notification sent to facility manager that alert system is offline.
