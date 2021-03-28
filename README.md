# Yii-ProjectorBorrowing
This is an app used to borrow projectors at different times

faculty
  id
  name
  
employee
  eid
  fName
  lName
  email
  telephpne
  f-idfk
  role-idfk
  
employee-role
  role-id
  role-name
  
projector
  id
  serial
  model
  
borrow
 id
 lender-employee-idfk
 borrower-employee-idfk
 start-time
 projector-idfk
 
report
  id
  borrow-idfk
  expired-flag (system time - start time)
  employee-idfk
  f-idfk
  status 1
  status 2
  status 3
  
  ==============================================================
          Home  Borrow  Settings  Report  login(admin)
  ==============================================================
  
  Setting => addRole  addFaculty  addEmployee addProjector
 
 
