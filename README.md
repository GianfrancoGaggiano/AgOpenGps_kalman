# AgOpenGps_kalman
THIS IS THE MODIFIED FILE FOR ADDING A KALMAN FILTERING TO HEADING CALCULATION OF AOGTREE, THE FILTER IS VELOCITY BASED. 
This means that the filtering will be greater at reduced speed or equal to 0 and will cancel itself as the speed increases. It is very useful in case the IMU is not used to stabilize
the fix to fix heading which would otherwise cause the orientation to rotate continuously. Location: \GPS\Forms

Here attached link to the video test for 360 degree rotation  with gps generator. https://youtu.be/WCbDmg35tP4

27/02/2021 added zip file with kalman version of AgOpengGps with speed dependent variable kalman filter, and use of IMU BRICK 2.0 mode 2 (no magnetometer) and it's roll filtered.

