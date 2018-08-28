# Move hack 2018

#### Road Safety:
Detecting places (areas) on a road where frequent aggressive behavior of various drivers is seen can be used to identify road conditions (potholes, speed breakers, slopes, U-turns/diversions, etc.).
We analyzed the danger zone or gray zone in Ahmedabad city.

Dependencies:
  - Python 3.*
  - Pandas
  - gmplot

#

#### Driver Behavior:
Major cause of road accidents depend on driver profiling. The intent of this proposal is to develop an algorithmic signature of driving type. Does a driver accelerate hard? Brake hard? Drive at high speed? Turn on curves at high speed or Change lanes at high speed? Answers to these questions combine to form an aggregate profile that potentially makes each driver unique.
##### Steps:
  - Data is collected using an Android App on mobile phone in CSV file for multiple trips. The generated file consists of following features:
      - GPS co-ordinates
      - Elapsed trip time
      - Speed (every second)
      - Angle of rotation of the vehicle
  - Machine learning model is trained with these features to predict a score of trip which is used as a deciding factor of driver behavior.
  - Driver behavior detection is useful in identifying and improving driver behavior, selecting drivers for various purposes or routes. And also insurance companies can change premium based on aggressiveness of the driver.



Dependencies:
  - Python 3.*
  - Pandas
  - Scikit Learn
  - xgboost
  - gmplot
