# OSProject
CSCI 3120 Summer 2017 Group Project

How to use:
              1)Make desired changes to files
              2)Type "make" in command line to compile
              3)In one terminal call ./sws N (where N is the corresponding port of the test)
              4)In another terminal call either (from tests folder):
                                                                      python hydra.py < TESTFILENAME.in (if you're running on Debian)
                                                                      ./hydra.py < TESTFILENAME.in      (if you're running on Mac)
                                                                      
 Format of a test.in file (described in detail in comments of hydra.py):
 
 X        //X = Port number being used for test
 A B S    //S = file name/location relative to sws, A = arrive time of S, B = request time of S
 C D T    //T = file name/location relative to sws, C = arrive time of T, D = request time of T
 ...
 ...
