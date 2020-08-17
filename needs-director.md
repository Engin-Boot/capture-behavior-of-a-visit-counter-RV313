# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given the patient visiting.
  
  When there are working days and holidays.
  
  Then to show the record of patient.

Scenario: Compute parking slots to reserve for visiting specialists

  Given the parking slots.
  
  When the specialists are visiting.
  
  Then to reserve the parking slots.
