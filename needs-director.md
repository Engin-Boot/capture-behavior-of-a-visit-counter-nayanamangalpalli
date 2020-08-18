# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given - patient visit count of working days and holidays
  When -  more patients are admitted in holidays than working days 
  Then -  emergency notification sent to director\
          availability of emergency beds and staff 

Scenario: Compute parking slots to reserve for visiting specialists

  Given - Limited parking slots
  When -  vehicles of visiting specialists exceeds a limit
  Then -  uses extra parking area
