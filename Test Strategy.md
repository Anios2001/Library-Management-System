# TEST STRATEGY 
The basic problem i faced while test running the application around 10 times was that of NULL Values.
So, I invoked NULL Testing.
//FAILED CASE 1
I made a seperate database which consisted of null values for the alternate Keys in the data base and checked what was the repurcussions of this input. 
The application was groping for data and there was no prompt indicating the user that an error occured.
// FAILED CASE 2
After resolving the null problem in the input, i tested the application on semi null data in order to confirm the procedures of data extraction and data demonstration.
The application stopped working on this data.
