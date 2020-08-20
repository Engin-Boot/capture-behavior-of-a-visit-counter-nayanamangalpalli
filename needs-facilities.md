# Visit-counter for a Facilities Manager

## Scenario: Report visitor trends during a week of operation

Given a system working 24/7 and consists of sensor and server
And: sensor collects number of visitors
And: server increments,stores visit count and generate report

When a sensor collects number of visitors entered in hospital

Then server provides a report of number of patients visiting hospital\
on daily and hour basis.\
(Patient visits hospital in evenings or weekend frequently)

## Scenario: Alert when seating capacity is full

Given a limited number of seats are available\
And: system consists of sensor which counts empty seats and server\
that sends alerts to manager

When two empty seats are remaining.

Then notification sent to facility manager that\
seating capacity will be full in while.
