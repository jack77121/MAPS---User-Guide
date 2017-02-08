# 系統設定 {#system-setup}

## 步驟 1. {#step-1}

**請先將您的 MAPS 機器插上電源線。**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/poweron_01.png)

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/poweron_02.png)

插電之後，紅色的燈號會先亮起，接著綠色的燈號會持續發亮，代表MAPS已經開機成功。

## step 2. {#step-2}

**Find the WiFi AP with the prefix “**_**LinkIt\_Smart\_7688**_**\_” in your WiFi configuration, and connect to this WiFi AP.**

**Then, the red LED of your MAPS will start blinking, meaning you are doing right so far.**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/findap.png)

For example, please join the WiFi network "LinkIt\_Smart\_7688\_1B2642" in the above example.

## step 3. {#step-3}

**Open your browser and go to**[**http://mapsOXOX.local/cgi-bin/luci**](http://mapsoxox.local/cgi-bin/luci)

**Note that “OXOX” is the device number \(four digits\) of your MAPS box, and you can find it easily on the top of your MAPS device.**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/mapssticker.png)

For example, the device number of the above MAPS device is 0020, and you have to go to[http://maps0020.local/cgi-bin/luci](http://maps0020.local/cgi-bin/luci)for the following steps.

## step 4. {#step-4}

**Please input the default password**_**iisnrl619**_**on the login page.**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/login.png)

## step 5. {#step-5}

**Please set up the GPS coordinates of your MAPS device by following the link \`System' and then \`GPS configuration'.**

**If you have no ideas about the GPS coordinates, please see FAQ.**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/gps01.png)

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/gps02.png)

Note that, the default GPS coordinates are on the Senkaku Islands, which means your measurement data will be placed there on the map unless you correctly setup the GPS coordinates.

## step 6. {#step-6}

**Now, the last step is to set up the WiFi of your MAPS device.**

**Please click \`System' and then \`MAPS configuration' for configuration.**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/maps_config01.png)

**Please input your WiFi SSID and PASSWORD information accordingly, and then click 'Yes, please'.**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/maps_config02.png)

## step 7. {#step-7}

**Your MAPS will reboot after step 6.**

**Please wait about 3 minutes, and the system will start working then.**

## step 8. {#step-8}

**Now, please go to the webpage**[**https://data.lass-net.org/grafana/**](https://data.lass-net.org/grafana/)

**Please click the device ID panel on the top left corner of the page, and input your device ID \(i.e., MAPS-OXOX\). Hopefully, you will find your device and the measurement data on the screen then!**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/grafana01.png)

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/grafana02.png)

