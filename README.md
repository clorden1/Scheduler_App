# Scheduler_App
**THIS REPO IS A WORK IN PROGRESS**

### About
The purpose of this repository is to create a desktop scheduling tool for pet grooming appointments. I want to create a free, local tool that makes managing groom schedules digitally easy and has features specific to a pet grooming use case.

As of this point the repo contains two files:
1. *classes.py* : A python script containing classes to be used in other scripts.
2. *functions.py*: A python script containing functions to be used in other scripts.

### Functionality
Functionality of this repository might include:
- Viewing groom schedules on a daily, weekly, and monthly basis.
- The ability to create new groom appointments with point-and-click functionality.
- Create client, pet and, groomer profiles.
- Confirm or cancel appointments with point and click functionality.
- View multi-level analytics to help understand trends.
- Ability to send confirmation requests via email.
- Ability to export/import/print data and schedules.

Future functionality to be considered could be:
- Ability to send confirmation requests via SMS.

### Method
For storing data, I will create a PostgreSQL database that will be communicated with through Python scripts. This is a free option for managing data.

The initial plan is to create seperate Python scripts to handle classes and functions and import these functions and classes into other scripts that run the program. My main reason for doing this is to enhance the readability and maintainablity of the code. A drawback to this is most likely going to be runtime. If runtime becomes too much of a problem, this structure will change.