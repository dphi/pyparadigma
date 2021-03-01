This project provides python tooling to extract metrics from Paradigma's SystaComfort II, SystaServiceLAN, maybe others, which do not provide a ModBus interface. It utilizes a proprietary udp-based protocol which operates on port 7260.


Pull requests are welcome.


This project is work-in-progress: 

* works
  * connect and recive data from a SystaComfort II
  * convert recieved data to values

* to-do
  * receive data for long periods of time, not just ~30s
  * understand the received values better
  * provide a plug-in interface to process the received data
  

This software is provided 'as-is', without any express or implied warranty. In no event will the authors be held liable for any damages arising from the use of this software.


Based on the great work from 
* https://www.haustechnikdialog.de/forum/t/152897/STAqua-2-Daten-auslesen
* https://www.vdr-portal.de/index.php?attachment/41077-paradigma-pl/
* https://forum.iobroker.net/assets/uploads/files/1554882672661-paradigma_heizung.pl

