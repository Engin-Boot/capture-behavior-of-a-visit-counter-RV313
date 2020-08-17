# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given  :patient visiting.
  
  When  :during the working days and holidays.
  
  Then  :Show the record of patient.

Scenario: Compute parking slots to reserve for visiting specialists

  Given :parking slots.
  
  When	:specialists are visiting.
  
  Then  :reserve the parking slots.
