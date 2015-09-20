JSON FORMATS FOR DATA
=====================

###These are some JSON formats for the various types of data being sent from Pod to Command and Command to Pod

###### Info (all data includes timestamp of when sent)
* GPS: includes latitude and longitude and what is the status of the pod at this location
* AIR QUALITY: includes oxygen percentages, says which dangerous element is there a prescence of, if it's safe or not, and if it's inside or outside the pod
* PRESSURE: includes pressure readings (units TBD),  if its safe, if its inside or outside the pod
* SONAR: includes distance from tube, quadrant (1-4 corresponding from North to West clockwise), and if it's safe or not,
* TEMPERATURE: includes temperature readings in celsius and farenheit,  if its inside our outside pod, and if it's safe or not

###### Danger
* Includes risk level, details of danger, suggested solution, timestamp, and type of info (corresponding to above section) to invoke for more details

###### Command
* Includes command, attributes to modify in case of emergency, so if you want to lower the speed but not brake, you would put the command as "custom", put "speed", and then put a value under values to modify, and you can do this for multiple attributes, it also includes a timestamp

###### Adding more

Feel free to add more JSON formats or ask me to add them
