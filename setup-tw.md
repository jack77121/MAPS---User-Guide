# 系統設定                                                                                    ![](/assets/logo.png) {#system-setup}

## 步驟 1. {#step-1}

**請先將您的 MAPS 機器插上電源線。**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/poweron_01.png)

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/poweron_02.png)

插電之後，紅色的燈號會先亮起，接著綠色的燈號會持續發亮，代表MAPS已經開機成功。

---

## 步驟 2. {#step-2}

**接著請在無線網路的清單中找尋以 "**_LinkIt\_Smart\_7688\__" 為起頭的網路基地台，並且加入該網路。

**此時 MAPS 上紅色的燈號會開始閃爍，代表目前為止的操作正確。**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/findap.png)

例如：在上方的範例中，您需要加入 "LinkIt\_Smart\_7688\_1B2642" 這個網路。

---

## 步驟 3. {#step-3}

**打開您的瀏覽器，並且前往這個網址：**[**https://mapsOXOX.local/cgi-bin/luci**](http://mapsoxox.local/cgi-bin/luci)

**請注意 “OXOX” 這個四位數的號碼，代表您的 MAPS 機器編號，這個號碼可以在盒子上方的貼紙上看到。**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/mapssticker.png)

例如：在上面這個範例中，MAPS 外盒上的號碼是 0020，因此必需前往這個網址：[https://maps0020.local/cgi-bin/luci](http://maps0020.local/cgi-bin/luci)

---

## 步驟 4. {#step-4}

**請在登入系統網頁中，輸入預設的密碼：**_**dolassgetmore**_

![](/assets/5.1.6login.png)

---

## 步驟 5. {#step-4}

**找到自己的GPS座標。**

**Android: 打開google map，長按所在地點**

![](/assets/android_map.png)

**iOS: 打開內建地圖 app，長按所在地點**

![](/assets/ios_map.png)

---

## 步驟 6. {#step-5}

選擇 'LASS-MAPS \(中\)'來進行 WiFi 和 GPS 的設定![](/assets/5.1.6_setting_tw.png)

---

## 步驟 7. {#step-6}

WiFi設定：

1. 點選 '掃描附近的 WiFi', 大約要5~6秒
2. 從 WiFi名稱選單選擇您的WiFi, 右邊的數字代表的是訊號強度 （0~100）. 例如：下方的範例我們選擇了 IIS\_Secure作為我們的WiFi, 它的訊號強度約70, 訊號強度尚可
3. 輸入WiFi密碼
4. 選擇 '我要使用WiFi'作為連線模式

GPS設定：

1. GPS來源選擇 '我要手動輸入'
2. 輸入緯度（步驟5）
3. 輸入經度（步驟5）

注意，MAPS 系統的預設地理坐標皆座落在釣魚台群島位置，若您未設定正確的座標，將來此機器的感測資料在進行地圖視覺化時，將會出現在錯誤的位置。

點選右下角的 'Save & Apply'

![](/assets/5.1.6_setting_wifi_gps_tw.png)

---

## 步驟 8. {#step-7}

**結束步驟 7 之後，MAPS 機器會自行重新開機。**

**喝杯水休息一下，耐心等候，系統約七分鐘後開始運作。**

---

## 步驟 9. {#step-8}

**現在，您可以前往這個網址：**[**https://data.lass-net.org/grafana/**](https://data.lass-net.org/grafana/)

**在網頁左上角的輸入區中，點選後輸入您的機器代碼（格式為 MAPS-OOXX），接著您在螢幕上將看到您的機器以及最新的量測結果。**

**注意，新設定的GPS將於隔日做更新，設定完的當下並不會馬上顯示正確的位置。**

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/grafana01.png)

![](https://jack77121.gitbooks.io/maps-v5-1-user-guide/content/assets/grafana02.png)

