# Software Components #

RICS is written in C++ using Microsoft Visual C++ Express 2008. wxWidgets, a GUI library, is used to implement the user interface. wxThreads, included in wxWidgets, is used to implement software threading. Image capture, image streaming (via the Ethernet network) and compression in the JPEG format are performed on a separate thread for each camera. The GPS data fetch and NMEA 0183 parsing is also performed on a separate thread. SQLite is used to store image file names and their corresponding GPS data, enabling images to be geo-tagged.