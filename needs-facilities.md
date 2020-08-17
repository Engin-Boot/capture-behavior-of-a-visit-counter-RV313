# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given the Visitor visiting
  and system is working
  we will assign id number to them
  When visitors will come during a week
  Then we will generate the report of visitors
  in excel sheet according to id numbers

Scenario: Alert when seating capacity is full

  Given the seating capacity
  and the system is working
  When the seating capacity is full
  the sensor will detect the void seats availability
  with the help of counter
  Then the alert will trigger
  if the counter is zero.
