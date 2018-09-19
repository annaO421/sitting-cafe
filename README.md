# sitting-cafe
shows the number of people in CAFE in real time

We use arduino D1 R1 board that the ESP8266 (wifi module) mounted to make connection between arduino and the server. So we also use PHP.
(ACTUALLY we recommend the D1 R1 board than only using ESP8266 module because of its instability..)

arduion.ino is the file that we use in arduino. It sends the sensor's data by GET response.

index.php is the main page's file of the web. This file gets the sensor's data by GET and also sends data to DB (We use mysql).

When you put the keyword in the search box, then the sch.php shows. This file shows the data searched by keyword in previous page. 
