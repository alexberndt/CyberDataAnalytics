## Cyber Data Analytics - Lab 3 ##

Group 60 - Ernst Mulders and Alex Berndt

### Running the Code ###

- The code was written in Python 2.7.12
- Install the packages specified in the requirements.txt file
- You can use the requirements.txt to install the package requirements
- We recommend using a clean virtual environment to avoid possible package conflicts

##### General Setup #####

- mkdir Group60Lab3
- git clone https://github.com/alexberndt/CyberDataAnalytics/ Group60Lab3
- cd Group60Lab3/lab3/
- pip install -r requirements.txt

##### Task 1 and 2 #####

The **main** file for Task 1 and 2 is ***readData.py***
this file runs the reservoir sampling as well as the min count sketch
- python2 readData.py

*The parsed csv file is already in the repository (this was done using parse_data.py, but you do not need to run it since it is already done!)*

##### Task 3 and 4 #####

For Task 3 and 4, run ***readDataQ3.py***
- python2 readDataQ3.py

Currently, the code runs the test.netflows file which is a sampled, parsed version of the large 500+ MB file of netflow traffic. This is just to improve the speed of the code.

You can download the full 500Mb file from here: https://www.dropbox.com/s/kpap4zoy77tv1x0/capture20110818.pcap.netflow.labeled.csv?dl=0

To process this file, just uncomment line 29 **reader = csv_read(...)** and comment line 30.
