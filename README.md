# OdbcArrayInsertCBinding
Copyright (c) 2016 Sathyanesh Krishnan. All rights reserved.

Licensed under the Apache License, Version 2.0;



## ODBC Array Insert with Colum wise Parameter Binding

This is an ODBC sample to demonstrate Array Insert Functionality (with Column wise parameter binding). 
In case of Colum wise Parameter Binding application pass arrays with column values. 
The insert cursor is turned on by SQL_INFX_ATTR_ENABLE_INSERT_CURSORS (a property specific to Informix), you may exclude this if you plan to run the code against other database. 
Thou the code is mostly generic; the VS 2015 Project given with the demo is created by linking with Informix ODBC driver library.


## Key properties application need to set

### The application set Attributes of   
* SQL_ATTR_PARAMSET_SIZE to specify the array size (the set of values in each array (bind to the parameter))  
+ SQL_ATTR_PARAMS_PROCESSED_PTR to specify the address of a variable in which the driver can return the number of sets of parameters processed, including error sets.  
+ SQL_ATTR_PARAM_STATUS_PTR to point to an array in which to return status information for each row of parameter values.  













