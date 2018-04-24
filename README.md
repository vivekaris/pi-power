# pi-power
this script will shutdown you raspberry pi using external button
# plz install gpiozero before setup
# sudo apt install python3-gpiozero
# connect button GPIO 21 and GND
# hold button for 2 second . your pi will be shutdown.
run below command to test
# python3 power_hold.py
# sudo nano /etc/rc.local
# python3 /home/pi/power_hold.py &
