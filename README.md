BUSINESS USE CASE:

Real time rash and reckless driving behaviour monitoring is a cornerstone to improving driving safety. Rash driving analysis for safety enforcement is a software system that analyses the driving pattern to derive insights based on his/her driving abilities. This system is also connected to the governmental authorities like the insurance companies and RTO systems that can ensure road regulations.
The insurance companies can charge variable premium from different drivers based on the neat or rash driving he/she has been doing. 
The RTO's can levy heavy penalties based on the driving skills that has been recorded over a period of time.
This system is indirectly creating awareness for safe driving and trying to improve the overall road sense and chaos and prevent accidents.

Technical feaures:

1) This system has an accelerometer(MPU6050) which keeps a track of the speed and most importantly change in the speed so that suddenly acceleration or sudden brakes can be tracked as these two factors are also called rash driving.

2)It uses VNC to establish a cloud connectivity between the Raspberry Pi 3(A smart IoT device) to the main server which generates insights.

3) Such communication can be controlled and passed on to the main server as well as the governmental authorities and insurance companies via the Message queuing telemetry transport protocol.

4) It uses the R programming to generate the insights from the raw data that the smart sensor is collecting real time and passing it through a comma separated file.

Output :

![alt text](https://github.com/urvi01/Rash-Driving-Analysis/blob/master/Hardware.JPG)

![alt text](https://github.com/urvi01/Rash-Driving-Analysis/blob/master/Analysis.JPG)

