This application was developed for CSS 432 - Databasing.
Team members included Brody Schulke, Christopher DuBois, Rob Stachofsky, and Phat Tran.

The following Database acts as a management system for various city Utility tasks that may need to be performed.
The Database also manages a larger overhead of various City Utiltiy Branches. 
The data emcompasses the following:
1. Utility Branch information
2. Addresses
3. Workers for the branches
4. Task schedules for workers
5. City utilities
6. Tasks for the various task schedules
7. The equipment to be used by the workers
8. Equipment required for a given task
9. The amount of equipment that is checked out from inventory

The database also employs various constraints to prevent bad scheduling or input data. 
These constaints include:
1. Preventing multiple task schedule dates from overlapping when assigned to a single worker
2. Invalid coordinates for the location of city utilities
3. Prevents task appointment times from overlapping within one task schedule
4. Prevents an invalid amount of equipment from being checked out from inventory