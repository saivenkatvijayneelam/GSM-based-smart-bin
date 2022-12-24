# GSM-based-smart-bin
We often see the garbage bins in public places to over flow over days without cleaning or collecting them ,this causes many problems to both environment and to people’s health..So to overcome this situation SMART BIN is helpful in emptying the bin in regular intervals.
By calculating the percentage of the bin filled in regular intervals with ultrasonic sensors and if the value crosses the threshold value it sends the coordinates to the server and the garbage collection vehicle using GSM to empty the respective bin.

what we have done- Integrating GSM, GPS , Sonar sensors with Arduino and calculating the distance and uploading the coordinates to the Thingspeak server if it crosses the threshold level. After uploading to thingspeak open those coordinates in app,and also sending notification to the garbage collection bin.

