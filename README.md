# TrafficLightARM
This is a code written for ARM processor that simulates a traffic light using GPIOs. One GPIO has three LED lights that represent a traffic light and the other is for an LCD display that
displays "WALK" or "STOP" messages depending on the state of the lights. <br><br>
Displaying messages on an LCD goes via a subprogram LCDWR. It takes ASCII code of a character that needs to be displayed. <br><br>
This is a project written for an assembler simulator I used for classes at college, so the addresses of GPIOs and RTCs are written according to specifications of our simulator. Adjust the addresses for your needs. <br><br>
