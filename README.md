# HW6 Report
## Our videos
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/MhdK6kJy5Co/0.jpg)](https://www.youtube.com/watch?v=MhdK6kJy5Co)
## Visual effects with ORB-SLAM2
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/CDbDI8bBeuw/0.jpg)](https://www.youtube.com/watch?v=CDbDI8bBeuw)


這是我們用mono_tum.cc所跑出來的影片。
ORB-SLAM2是完整的SLAM系統，基於所提取出來的稀疏特徵點，
作到localiztion以及mapping的效果。

## Visual effects with any post-production software
* 威力導演15
這個影片是利用威力導演中，動態追蹤這個功能，使文字可以根據物體位置移動。
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/xfSLMkTO-_o/0.jpg)](https://youtu.be/xfSLMkTO-_o)

Step1 點選影片選擇動態追蹤

![](https://i.imgur.com/Xw6vLIk.png)

Step2 選定自己欲追蹤的物件，輸入文字後，軟體會自動將文字釘選在物件上，使物件隨著物體位置移動。

![](https://i.imgur.com/8AEtaOK.png)

* Adobe After Effects

AE有motion tracker跟3d camera trcaker功能，不過我們的AE版本似乎較舊因此沒有3d camera tracker，所以我們是使用motion tracker。

motion tracker可以簡單的將標的標記在某物體上，之後便能追蹤那個物體得到運動軌跡，就能將文字或是圖片跟著目標物體移動了。

影片中一開始是在主機上放上一朵花，然後再讓隔壁的滑鼠變成一隻小白鼠。





### 
## Compare above methods
||ORB SLAM2  |威力導演|After Effects|
|--|---------|------    |-------------|
|操作困難度    | 非常困難  |簡單| 簡單        |
|效果|  好     |差        |  一般       |
|執行時間      | 快       |快|  一般     |

* ORB-SLAM2
ORB-SLAM2首先會對圖片提取特徵並計算出descriptor, 接著再對每一張圖片做feature matching, 並利用這些matching的結果來推算出相機運行的軌道。ORB-SLAM2在執行方面上很快，不需要GPU的加速即可在一般CPU上執行，效果也很好，但是環境安裝上相較複雜。

* 威力導演
威力導演中動態追蹤的功能，讓使用者可以輕鬆的選取欲追蹤的物件，整體軟體介面也讓使用者可以輕鬆的選擇欲釘選的物件，但效果上並沒有想像中的好，當影片的視角轉換時，釘選的物件會較不自然。
* After Effects
AE有較多種追蹤的方式，但是由於功能太多且複雜，實作前需要看許多教學影片。當影片拍攝晃動較大時，動態追蹤會較不靈敏，會與實際物體位置產生一點誤差，但是整體效果看起來還不錯。
## Special effects
### zoom in 
#### original video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/APqdNaLJVfI/0.jpg)](https://www.youtube.com/watch?v=APqdNaLJVfI)
#### Enhance video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/PaXWVnloN48/0.jpg)](https://www.youtube.com/watch?v=PaXWVnloN48)

我們利用Camera Tracking的功能，幫助我們改進zoom in 的效果

## Insert a 3D model

## Conclusion
