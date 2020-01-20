# WeatherStationData
A collection that interacts with an Oregon Scientific weather station. Data is uploaded to a MySQL database, and can be retrieved via an Android application or C# Desktop Application.

Credit goes to user robwlakes for his ingenius decoding of the Oregon Scientific weather devices. Using his decoding algorithm, I was able to modify the sketch to run on an ESP8266, connect to local Wifi and upload to an AWS MySQL database. Currently, I am working on a Windows Desktop Application to access and display this information as well as an Android application with the same goal. The first version of the desktop application should be here in the coming weeks and the android app shortly afterward.

Future goals will include accessing specific dates information and comparing the data to predictions from mainstream weather forecasting sites.

Update: robwlakes has done a lot of work updating his Rx algorithm! He's also designed and printed his own weather station, an amazing feat in itself. I encourage you to check out his work at the following links. 

https://www.thingiverse.com/thing:2849562
https://www.thingiverse.com/thing:3546977
