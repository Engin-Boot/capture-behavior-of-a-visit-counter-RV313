# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given the system is on
  and the patient visits
  we allocated them the ID number
  When we are having working days and holidays
  Then show the record of patient visiting in excel file as per ID number
  
Scenario: Compute parking slots to reserve for visiting specialists

  Given the parking slot and the sensor for identifying vehicle
  When the specialists are visiting
  we can give names to the slots
  Label as filled if specialists parks at the allocated slot
  Then we can reserve the parking slots for specialists
