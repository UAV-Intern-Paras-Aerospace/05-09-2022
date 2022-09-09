task was to read temetory data from the flight controller using arduino nano
Arduino nano clone has very poor driver support and it is very basic arduino with very small dynamic memoery and only one hardware serial port tried to implement it using software serial, also tried to reduce the computational footprint of the program but nothing worked.                             
MAVLink inspector was not showing any Data_request from the arduino
   
Tried 3 methods for data request from arduino and mission planner 
1)REQUEST_DATA_STREAM                                                                                           
2)SET_MESSAGE_INTERVAL
3)REQUEST_MESSAGE (COMMAND_LONG API)
