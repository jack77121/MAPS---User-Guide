# System Setup                                                                            ![](/assets/logo.png)

## step 1.

**Power on your MAPS by connecting the power cable to your MAPS device.**

![](/assets/poweron_01.png)

![](/assets/poweron_02.png)

The red LED will shine for a while, and then the green LED will keep lighting after MAPS becomes ready.

## step 2.

**Find the WiFi AP with the prefix “**_**LinkIt\_Smart\_7688**_**\_” in your WiFi configuration, and connect to this WiFi AP. **

**Then, the red LED of your MAPS will start blinking, meaning you are doing right so far.**

![](/assets/findap.png)

For example, please join the WiFi network "LinkIt\_Smart\_7688\_1B2642" in the above example.

## step 3.

**Open your browser and go to **[**https://mapsOXOX.local/cgi-bin/luci**](http://mapsoxox.local/cgi-bin/luci)** **

**Note that “OXOX” is the device number \(four digits\) of your MAPS box, and you can find it easily on the top of your MAPS device.**

![](/assets/mapssticker.png)

For example, the device number of the above MAPS device is 0020, and you have to go to [https://maps0020.local/cgi-bin/luci ](http://maps0020.local/cgi-bin/luci)for the following steps.

## step 4.

**Please input the default password  **_**dolassgetmore**_**  on the login page.**

![](/assets/5.1.6login.png)

## step 5.

**Prepare your GPS coordinates.**

Android - open google map app, hold on your locaton

iOS - open Maps app, hold on your location![](/assets/find_gps.png)

## step 6.

**Please set up the WiFi & GPS coordinates of your MAPS device by following the link 'LASS-MAPS \(EN\)'**

** **![](/assets/5.1.6_setting.png)

## step 7.

**Few more steps below,**

**For WiFi Setting:**

1. Click the button "Scan WiFi nearby" for WiFi scanning, it takes about 5~6 secs.
2. Choose the WiFi ID from the list, the number presents the signal strength \(0~100\). For example, the picture below shows that we choose the AS\_Guest as our WiFi ID, and its signal strength is 68, not so well.
3. Enter the WiFi password.
4. Select 'Use WiFi'. 

**For GPS Setting:**

1. Select 'Input manually.' as your GPS Source.
2. Input your Latitude. \(Step 5\)
3. Input your Longitude. \(Step 5\)

Note that, the default GPS coordinates are on the Senkaku Islands, which means your measurement data will be placed there on the map unless you correctly setup the GPS coordinates.

Click 'Save & Apply', the blue button in the bottom right corner.

![](/assets/5.1.6_setting_wifi_gps.png)

## step 8.

**Your MAPS will reboot after step 7.**

**Have a cup of tea, the system will start working about 7 minutes later.**

---

## step 9.

**Now, please go to the webpage **[**https://data.lass-net.org/grafana/**](https://data.lass-net.org/grafana/)

**Please click the device ID panel on the top left corner of the page, and input your device ID \(i.e., MAPS-OXOX\). Hopefully, you will find your device and the measurement data on the screen.**

![](/assets/grafana01.png)

![](/assets/grafana02.png)

