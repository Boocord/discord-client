# Boocord
A Lightweight Discord Client Built with Nativefier

![image](https://github.com/Boocord/discord-client/assets/85783692/1fc05191-fbc5-4e41-94df-7e7607b0fa43)


# Statistics
These tests were done on:
- AMD Ryzen 7 7840HS 3,80 GHz
- 16GB DDR5 RAM
- SK Hynix PC801 HFS001TEJ9X10N SSD

|  |Boocord|Discord|
|--|--|--|
|Ram usage:|30MB|579MB|
|CPU usage:|%0|%2.5|
|App size:|231MB|474MB|
|Installer size:|68.7MB|107.1MB|

# Does this go against the T.o.S.?
In technicality, as this is still a build of the [discord.com](https://discord.com) website, it does not violate the T.o.S. since it is not a custom client but rather a different runtime or browser. If we assume that electron is just a one page web browser that is extremely minimal and that no changes are being made to the website, this is not against the t.o.s. 

# Building
prerequisites: Npm (Nodejs)
```
$ npm install nativefier
$ nativefier --name 'Boocord' 'discord.com/app' --disable-gpu --tray -u "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36 uacq"
```
