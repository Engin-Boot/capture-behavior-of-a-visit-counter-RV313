# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given system computing visit-count
  When the server goes down suddenly
  Then the recover across restarts the server

Scenario: Reconcile counts if the sensor is offline for a while

  Given Sensor is online
  and working
  When the sensor is offline
  Then Reconcile count
