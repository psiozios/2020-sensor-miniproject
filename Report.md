

TASK 0

The greeting string issued by the server to the client upon first connecting is:
  "ECE Senior Capstone IoT simulator"
  
  
TASK 1

Provided in the repository is the Python code for Websockets client that saves the JSON data to a text file as it comes in (message by message).


TASK 2

The data points observed were printed to the command line for ease of access to the user.
The median and variance observed from the temperature data (with at least 100 values) in the office is 23.011 degrees and 1957.36 respectively.
The median and variance observed from the occupancy data (with at least 100 values) the office is 2 people and 1.972 respectively. 
Provided in the repository is code (named analyze.py) for the histogram plots of the data.

The mean and variance of the time interval of the sensor readings are 1.014 and 1.021 respectively. 
Plots of the time interval in histogram format can be obtained from running the code in the repository. 
The plot does mimic the Erlang distribution for connection intervals in large systems, because many time sensitive systems obey this specific PDF pattern where the probability of higher delays decreases exponentially.


TASK 3

Provided in the repository is an algorithm (named anomaly.py) that detects anomalies in temperature sensor data, prints the percent of "bad" data points and determines the temperature median and variance with these bad data points discarded.

A persistent change in temperature does not always indicate a failed sensor - in an environment where temperature is volatile, the readinngs can vary widely within a shorter period of time. It will depend more on the environment the sensor is placed in.

Accounting for the several different climates around the world, possible bounds on temperature for each room type can be 0 to 50 degrees Celsius. However, a more reasonable spread would be between 17 and 27 degrees Celsius, where air conditioning and heating play bigger factors in sensor readings. 


TASK 4

how is this simulation reflective of the real world?

how is this simulation deficient? What factors does it fail to account for?

how is the difficulty of initially using this Python websockets library as compared to a compiled language e.g. C++ websockets

would it be better to have the server poll the sensors, or the sensors reach out to the server when they have data?
