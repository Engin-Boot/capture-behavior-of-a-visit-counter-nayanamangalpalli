# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

Given a server is on\
When server restarts\
Then current count of patients saved in storage.

Scenario: Reconcile counts if the sensor is offline for a while

Given a counting system consists of sensor,server\
And: senor is offline

When patients visits a hospital\
Then system allows to enter patient count manually to a server
