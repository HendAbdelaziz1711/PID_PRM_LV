# PID_PRM_LV
Parameter Extraction of S-shaped response to step input to be used in PID ZN method. 

## For plants that exhibit an s-shaped output to a step resonse
The S-shaped response is characterized by 3 parameters: the gain (k), time delay (L), and the time constant (T). 
These parameters can be obtained from the response by finding the tangent to the curve with the highest slope, then finding the intersection points between this tangent and the time axis, and the intersection between the tangent and the horizontal line where the response settles. 

The code extracts these parameters from any response that the user enters. Given the user enters values for the output and time recorded from the experiment. 
![image](https://github.com/user-attachments/assets/c23098a0-379e-4dd4-90fc-d661d5061d5a)
