# mad-final

The App:-

The app is a mobile banking app that works on the basis of intent calls, mathematical operations and a backend database management. The app aims to fulfill a couple of functions:-

a. Availability of a checkings and savings account.
b. The ability to deposit and withdraw funds in both. User also cannot withdraw more than the amount he/she currently has.
c. An actionlog using SQLiteOpenHelper, extended by a user defined class called DBHelper. Shows the activities performed by a user and can be accessed from the backend (device file resource manager).

Brief Logic:-

The app opens to a login and password screen (username: 1, password: 1). User is given 3 choices: (i) Access to savings account (deposit and withdraw money); (ii) Access to Checkings account; (iii) Transfer Money between checkings and savings. These operations are taken care of, by using intent calls and button OnClick methods. If conditions are put in place in order to make sure the user does not withdraw or transfer more money than he/she already has. 

Lastly, the app also uses shared preferences to store user balance data.