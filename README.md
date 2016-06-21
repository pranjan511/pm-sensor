# Urban sensing system with PM 2.5 sensor#
Urban sensing system with PM 2.5 sensor exchanges messages between PM 2.5 sensor & raspberry. 
It logs the sensed data with timestamp. This project uses c library to read the values of the sensed data by PM 2.5 sensor.

Required hardwares:
1. PM 2.5 sensor from shinyei (know more at: http://www.shinyei.co.jp/stc/optical/main_pm2_e.html)
2. Raspberry pi model B,
3. Li-ion battery,

Required software packages:
1. Flash the Raspberry pi with Raspbian or NOOBS,
2. Install the python 2.7 or higher,
  (using sudo-apt-get install python 2.7)

connect the raspberry with shinyei PM2.5 sensor using LAN ethernet cable. 
Run the shell script which internally calls the c library executable to communicate with sensor 
and starts sensing the PM 2.5 sensor and logs the data into filesystem.
