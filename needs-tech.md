# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

Given a server restarts\
When it restarts while counting number of patients\
Then current count of patient not considered

Scenario: Reconcile counts if the sensor is offline for a while

Given a counting sytem consists of sensor,server and senor is offline\
When patients enters hospital\
Then system allows to enter patient count manually to a server
