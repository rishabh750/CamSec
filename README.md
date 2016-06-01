# CamSec
Home/Office Security system (Computer Vision Systems on MATLAB)

CONTENTS

1. Introduction
2. Project Files included
3. Instructions for Execution
4. Conclusion

1. INTRODUCTION

CameSec is a Home/Office Security Software coded in MATLAB.
It is a very simple implementation of Digital Image Processing which uses entry level 2D image matrix operations.
The algorithm can be further improved by passing the image matrix to a GPU but the fetching cycle takes lot of time and thus the modification has been left out for future considerations.

2. PROJECT FILES INCLUDED

The project consists of the following major codes which are further assisted with there figure files:-

  2.1. LOGIN.M: Initiates the program. Provides a prompt for user to login. The system consists of mainly two users, superuser and an observer.

    Superuser has the feature of specifying the sensitivity of the system to localize an intruder.
    Observer has resticted access and can only observe thhe output and cannot make any input to the sysstem.

  2.2. TRAIN.M: Executes the Superuser interface
  2.3. GAURD.M: Executes the Observer interface

  2.4. Sensitivity.txt: Stores the Sensitivity of the algorithm. Can be updated by the superuser. Observer inputs the sensitivity form this file and implements the algorithm while passing this sensitivity as an argument.
  
To start the application, run LOGIN.M

3. INSTRUCTIONS TO EXECUTE

Follow the following instructions:-
  3.1. Clone the project onto your system
  3.2. Open LOGIN.M in MATLAB
  3.3. Now you have two options
    3.3.1. Directly execute the matlab file
    3.3.2. Create a standalone

4. CONCLUSION

Do let us know about the performance and accuracy of the algorithm. If you can come up with a faster algorithm please share. The project is opensource and we encourage sharing of different test results.