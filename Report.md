

TASK 0

The greeting string issued by the server to the client upon first connecting is:
  "ECE Senior Capstone IoT simulator"
  
  
TASK 1

Provided below is the Python code for Websockets client that saves the JSON data to a text file as it comes in (message by message):


TASK 2

what are the median and variance observed from the temperature data (at least 100 values) [3 points]
what are the median and variance observed from the occupancy data (at least 100 values) [3 points]
plot the data histogram for each sensor type [6 points]
What is the mean and variance of the time interval of the sensor readings? Please plot the time interval histogram. Does it mimic a well-known distribution for connection intervals in large systems? [8 points]


TASK 3

Provided below is an algorithm that detects anomalies in temperature sensor data, prints the percent of "bad" data points and determines the temperature median and variance with these bad data points discarded:

Does a persistent change in temperature always indicate a failed sensor?
What are possible bounds on temperature for each room type?


TASK 4

how is this simulation reflective of the real world?
how is this simulation deficient? What factors does it fail to account for?
how is the difficulty of initially using this Python websockets library as compared to a compiled language e.g. C++ websockets
would it be better to have the server poll the sensors, or the sensors reach out to the server when they have data?
