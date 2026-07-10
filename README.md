# -encapsulation-smart-door-system
Objective: Develop a smart door access system for UMaT admin staff.  
Objective: Develop a smart door access system for UMaT admin staff.

Class Design: Create a Staff class.

Attributes:

Public: s_name (staff name).

Private: __access_code (staff’s access code, protected from direct modification).

Methods/Functionality:

View the access code (restricted to authorized users).

Update the access code with validation (e.g., minimum length requirement).

Display staff information (name and access code).

Implementation Detail: Use the @property decorator to manage the access code instead of traditional getter and setter methods
