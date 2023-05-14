# 操作說明

- 務必先將鍵盤[安裝完畢](guide.md)後再來看操作說明。

## （一）安裝雲台腳架

### A、雲台安裝需求

- 探索者1號是完全支援雲台的分離式鍵盤，沒有其他的安裝方式，但也不是什麼雲台配件都可以使用，這裡我會列出以下幾點安裝雲台時的要求：
  - 底板面積要大。
  - 底座要比單手鍵盤本體重量要重。

- 建議配置[Arca快拆系統](https://www.google.com.tw/search?q=arca+tripod&sxsrf=APwXEddPAT1f29tii0hugS33QeRQuseIqA%3A1684040734940&ei=HmxgZLWHOZiD-AadibfoCw&ved=0ahUKEwi1jqzOhPT-AhWYAd4KHZ3EDb0Q4dUDCBA&uact=5&oq=arca+tripod&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQA0oECEEYAFAAWABgAGgAcAF4AIABAIgBAJIBAJgBAA&sclient=gws-wiz-serp)：
  - 留意整體大小不要衝突主控座，特別是有線TRRS座主控座的安裝。
  - 穩固鍵盤本體。
  - 快速拆卸雲台，方便直接調整底座的角度。

### B、雲台安裝步驟

- 以下說明並非廠商廣告，請當作參考閱讀。
- 作者我本人使用的雲台配件如下，[SmallRig](https://www.smallrig.com/)：[1092](https://www.smallrig.com/cool-cheese-plate-v3-multi-purpose-mounting-plate-1092.html)、[2065](https://www.smallrig.com/smallrig-articulating-arm-5-5-inches-2065.html)，[Falcam](https://www.falcam.com.cn/)：[F38 series 2400（2465）](https://www.falcam.com.cn/falcam-f38-pd-quick-release-plate-2465_p64.html)、[2401](https://www.falcam.com.cn/falcam-f38-anti-deflection-quick-release-plate-2401_p61.html)。
<img src="image/manual/1-1.jpg" style="zoom: 50%;" >

- 首先安裝單邊魔術手臂到洞洞板的位置上。
<img src="image/manual/1-2.jpg" style="zoom: 50%;" >
<img src="image/manual/1-3.jpg" style="zoom: 50%;" >

- 再將魔術手臂角度稍微調整一下。
<img src="image/manual/1-4.jpg" style="zoom: 50%;" >

- 將魔術手臂鎖緊固定好。
<img src="image/manual/1-5.jpg" style="zoom: 50%;" >

- 將Arca快拆系統母座安裝上去。
<img src="image/manual/1-6.jpg" style="zoom: 50%;" >

- 再將另一支手臂安裝好。
<img src="image/manual/1-7.jpg" style="zoom: 50%;" >

- 接著將Arca子板安裝在鍵盤雲台上。
<img src="image/manual/1-8.jpg" style="zoom: 50%;" >

- 螺絲鎖緊。
<img src="image/manual/1-9.jpg" style="zoom: 50%;" >

- 接著就可將鍵盤安裝在底座上了。
<img src="image/manual/1-10.jpg" style="zoom: 50%;" >

- 完成會是這樣的感覺：
<img src="image/manual/1-11.jpg" style="zoom: 50%;" >

- 最後再調整魔術手臂的角度，選定一個喜歡的角度後再將魔術手臂固定好。
<img src="image/manual/1-12.jpg" style="zoom: 50%;" >

- 接上TRRS線。
<img src="image/manual/1-13.jpg" style="zoom: 50%;" >

- 再將鍵盤連接到電腦。
<img src="image/manual/1-14.jpg" style="zoom: 50%;" >

- 完成！
<img src="image/manual/1-15.jpg" style="zoom: 50%;" >

## （二）排線原理及VIAL QMK按鍵設定

### 排線原理

- 閱讀到操作說明這邊的讀者，假如你/妳是按照標準的排線安裝流程組裝鍵盤的話，這邊會告訴你這樣做的原理：
<img src="image/manual/2-1.png" style="zoom: 50%;" >

- 除了將矩陣用排針的形式拓展之外，這樣做的原理還可以當作另一種開關的形式。打個比方：我要在4x5主配列上做1列的拓展，就將拓展上的排線接上去，鍵盤就會立即辨識。也就是說，在還沒有接上拓展排線時，鍵盤拓展為Off，接上的時候為On。

- 也就是說，你要使用拓展，就將拓展的排線接上去，底殼螺絲鎖上，這樣就可以無痛升級。

### VIAL按鍵設定

- 探索者1號不限配列，統一使用一個韌體，這樣設計的原因為增加鍵盤的可玩性，接著來說明VIAL要如何改按鍵。
- 首先進入VIAL，探索者的鍵盤排列會長這樣：
<img src="image/guide/6-1.png" style="zoom: 50%;" >

-簡單介紹一下物理層面控制的位置，所有框起來的部分是可依據現有配列去做更動的，沒有用到那顆按鍵或是沒有那顆（排）按鍵，就不要在那個位置設定鍵位，即使你設定了，你也沒辦法讓電腦辨識。
<img src="image/manual/2-2.png" style="zoom: 50%;" >

- 打個比方，作者本人的配列屬於3x6+3，合計42鍵的鍵位，因此在VIAL上，我可以設定鍵位的地方如下：
<img src="image/manual/2-3.png" style="zoom: 50%;" >

- 沒有被紅色區塊框起來的地方就算有設定鍵位也沒辦法按，這點大家在改按鍵的時候特別注意。

## （三）基礎配列

- 探索者1號在設計的時候是以同一個拇指區基座為基底設計，有3x5及4x5可以選擇。

### A、3x5配列
<img src="image/manual/3a-1.png" style="zoom: 50%;" >


### B、4x5配列
<img src="image/manual/3b-1.png" style="zoom: 50%;" >



### C、3x6配列
<img src="image/manual/3c-1.png" style="zoom: 50%;" >



### D、4x6配列
<img src="image/manual/3d-1.png" style="zoom: 50%;" >



## （四）拇指區



### A、拇指區基座




### B、底板




### C、按鍵數量




## （五）特殊配列



### A、標準VIAL預設配列
<img src="image/manual/5a-1.png" style="zoom: 50%;" >



### B、左手4x5+3、右手3x6+3
<img src="image/manual/5b-1.png" style="zoom: 50%;" >



### C、左手3x6+3、右手標準VIAL配列
<img src="image/manual/5c-1.png" style="zoom: 50%;" >






## （六）結語
















