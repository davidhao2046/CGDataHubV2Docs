
---
<div class="notes">
  文档更新日期：2019-09-27</p>
</div>

### **数据时间**
目前常用的时间有两种，包括北京时（GMT +8）和世界时（GMT +0）
<img src="DataDetails/dataTimeList.png" alt="文件时间列表" class="dataFlowImg" />



**世界时**

<img src="DataDetails/satelliteGMT.png" alt="卫星云图文件时间" class="dataFlowImg" />

1. 如果数据文件名上的时间跟编辑时间差8个小时左右则为世界时间。

### **雷达数据**

基本反射率产品是雷达基本观测量，单位为Dbz
<div class="notes">
  <p><strong>备注：</strong><br> pup雷达文件名格式:<br> 
20170622.1003001.02.19.10 <br> 
年月日.时分秒.仰角（02表示15度）.产品.公里（目前常用230）</p>
</div>


<p class="imgTitle">雷达数据配色条</p>
<img src="DataDetails/radarLegend.png" alt="雷达配色条" class="dataFlowImg" />

**参考链接：**

<a href="http://www.weather.com.cn/radar/" target="_blank">天气网雷达页面</a>

### **卫星云图**

目前普遍使用的是风云2号红外云图，以后会切换到风云4号红外云图。

**参考链接:**

<a href="http://www.weather.com.cn/satellite/" target="_blank">天气网云图页面</a>
<br>
<a href="http://himawari8.nict.go.jp/zh/himawari8-image.htm" target="_blank">向日葵8号网页</a>

### **地面观测**

地面观测即自动站数据。
<div class="notes">
  <p><strong>备注：</strong>自动站数据只有整点气温是当前时刻的，其它数据都是上一时次的数据。举例：13到的数据，只有整点气温是13点的，其它的数据都是12：00到12：59的数据，例如降水，一小时最高温。
</div>


---
地面观测、数值预报、雷达、云图、城镇预报、台风路径和旅游