                   
Introduction
-----------------
Disk speed test using dd utility
                   
GIT Repo Location
-----------------
https://github.com/pszaro/disk-speed-test.git
                   
List of Scripts
-----------------

  - [disk_speed_test.sh]:
   Determine speed of write/read on drive command executed on
                   
Things to do
-----------------

Utilities Needed: 


- dd - The dd utility copies the standard input to the standard output. Available on macOS and *nix


- - - - - -

Things to know/change before first run:


-Script will run 10 iterations of write/reads of a 1GB file called tstfile (Adjust if you want different parameters)

-After executing through 10 iterations, it will calculate the average for write and read speeds

-Script generates a log of each run and dumps the average to the location specified for LOG. (Update the location if you want it logging to a different location.)


Example of log:


Performed on /Volumes/DATA - 20180209145637 
Average Write Speed Over 10 Iterations: 1316.03
Average Read Speed Over 10 Iterations: 1627.87


