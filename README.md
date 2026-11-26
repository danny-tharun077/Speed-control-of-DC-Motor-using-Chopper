# Speed-control-of-DC-Motor-using-Chopper
Speed control of DC Motor using Chopper

## AIM
To simulate and analyze Speed Control of DC motor using Chopper using MATLAB/Simulink.

## APPARATUS REQUIRED
•	MATLAB

## PROCEDURE
1.	Open MATLAB and click on the icon for SIMULINK as shown below
 <img width="522" height="376" alt="image" src="https://github.com/user-attachments/assets/383aa109-e162-4df4-9b46-0568207add77" />

Another way is to open is through START icon of MATLAB Start ⇒ Simulink ⇒ Library  browser. 

2.	Click on NEW MODEL or go to FILE ⇒ NEW ⇒ MODEL and a new blank model is created as shown below
 <img width="572" height="382" alt="image" src="https://github.com/user-attachments/assets/5da4ce35-0318-4e5a-b371-41f9626f9d10" />

3.	After creating a blank model you need to open the SIMULINK component storeroom/library by going to View ⇒ Library Browser. Select SIMPOWER SYSTEMS then select Power Electronics library and by right clicking on diode and click on add to the model will add the diode in the blank model. Alternatively you can drag the component directly in the model page as shown below
 <img width="940" height="361" alt="image" src="https://github.com/user-attachments/assets/6eee031c-f343-47be-b102-f2fd1c00a958" />

4.	Create a model for Speed Control of DC motor using Chopper as shown below
 <img width="940" height="379" alt="image" src="https://github.com/user-attachments/assets/4eed6be3-45e9-4c44-98a3-38399ac7bf47" />

5.	Run the simulation 
6.	Vary the Duty cycle and note down the Voltage and speed
7.	Save the file. 
8.	Analyze and record your inference.

## CIRCUIT DIAGRAM
<img width="1245" height="615" alt="image" src="https://github.com/user-attachments/assets/9ab1dea1-85d0-49db-a529-a7838eb10e6c" />

### OBSERVATIONS

| Duty Cycle (%) | Ideal Chopper Output Voltage (V) | Approximate Motor Speed (RPM) |
|---------------:|---------------------------------:|------------------------------:|
| 0              | —                                | —                             |
| 10             | 110.3                            | 542.9                         |
| 20             | 124.2                            | 673                           |
| 30             | 142                              | 840.2                         |
| 40             | 165.8                            | 1063                          |
| 50             | 199.1                            | 1375                          |
| 55             | 221.3                            | 1583                          |
| 58.33          | 239.1                            | 1749                          |



## Result
Thus to simulate the speed control of DC motor using chopper has been simulated and verified successfully.
