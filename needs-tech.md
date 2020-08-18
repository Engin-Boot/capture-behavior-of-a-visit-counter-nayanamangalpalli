# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given - restarts a server\  
  When - while counting of patients it restarts\
  Then - current count of patient not considered

Scenario: Reconcile counts if the sensor is offline for a while

  Given - sersor is offline and counting patients manually\
  When  - during reconcile if multiple patient enters hospital\
  Then  - executes both process of reconcile and counting of patient parallely 
