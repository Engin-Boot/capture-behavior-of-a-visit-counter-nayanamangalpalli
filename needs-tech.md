# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

Given a server is on\
When server restarts\
Then count of patient backuped up in storage.

Scenario: Reconcile counts if the sensor is offline for a while

Given a counting sytem consists of sensor,server and senor is offline\
When patients visits a hospital\
Then system allows to enter patient count manually to a server
