# NMEA2000 Display App
Welcome to our NMEA2000 Display App repository. This simple but powerful web app, in conjunction with our iKonvert USB gateway, can display all PGNs and Devices on your NMEA2000 network. 

Written in HTML5, the app uses Web Serial APIs, to accesss the iKonvert's USB Serial port at 230400 baud. As long as the iKonvert USB is in its default Mode 0 and the internal DIP switches have not been moved, the app will autodetect the iKonvert USB, set it to Mode 15 (RAW NMEA2000 mode) and start to read data.

This is the world's first multi-platform NMEA2000 display program and whether you use Windows, LINUX, Mac OSX or Raspbian this simple app (single HTML file) which requires no installation, will allow you to see exactly what is happening on your NMEA2000 network.  
