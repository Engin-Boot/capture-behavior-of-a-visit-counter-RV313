# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given the system is on and the patient visits and we allocated them the IDs
  When we having working days and holidays
  Then show the record of patient visitin in excel file as per IDs

Scenario: Compute parking slots to reserve for visiting specialists

  Given the parking slot and the sensor for identifying vehicle
  When the specialists are visiting we can give names to the slots and put the filled if specialists parks at the slot
  Then we can reserve the parking slots for specialists
