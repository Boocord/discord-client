# Boocord
A Lightweight Discord Client Built with Nativefier

![image](https://github.com/Boocord/discord-client/assets/85783692/fc6d0490-49b0-4705-9fee-12c31b6f6239)

# Statistics
These tests were done on:
Intel(R) Core(TM) i5-2520M CPU @ 2.50GHz
8GB DDR3 RAM
INTEL SSDSA2BW160G3L SSD DISK

|  |Boocord|Discord|
|--|--|--|
|Ram usage:|32MB|324MB|
|CPU usage:|%0|%26.5|
|App size:|145MB|387MB|
|Installer size:|60MB|91MB|

# Does this go against the T.o.S.?
In technicality, as this is still a build of the [discord.com](https://discord.com) website, it does not violate the T.o.S. since it is not a custom client but rather a different runtime or browser. If we assume that electron is just a one page web browser that is extremely minimal and that no changes are being made to the website, this is not against the t.o.s. 

# Building
prerequisites: Npm (Nodejs)
```
$ npm install nativefier
$ nativefier --name 'Boocord' 'discord.com/app' --disable-gpu --tray -u "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/112.0.0.0 Safari/537.36 uacq"
```
