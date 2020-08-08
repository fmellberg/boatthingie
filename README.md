# boatthingie
Something boat IoT and NMEA

I got an Arduino UNO to make something of.
A boat, with a GPS-reciever and an interface box for the nav system that sends out NMEA Sentences.

So the boatthingie must:
====

- plug into the interface box
- recieve data (NMEA) as it is made available
- hold the data in some kind of solid state

With wifi-card:
====

- connect to internet
- send NNMEA data by consuming a web API
- configure WiFi-conntection

First iteration:
====

Plug in to interface box and Read and store serial data
