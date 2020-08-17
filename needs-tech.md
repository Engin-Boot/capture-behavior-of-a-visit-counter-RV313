# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter
 
  Given : computing visit-count.
  
  When	: the server unexpected shut-down.
  
  Then	: recover across restarts of server.

Scenario: Reconcile counts if the sensor is offline for a while

  Given	: Sensor is online.
  
  When	: If the sensor is offline.
  
  Then	: Reconcile counts.
