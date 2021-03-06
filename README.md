# Centrality Word-Cloud
## 项目说明
>本项目涉及一种适用于LBS兴趣点多维度信息表达的词云生成方法，采用JavaScript编程语言实现中心-力导向模型的构建，然后利用[D3.js](https://d3js.org/)将表征兴趣点的标签符号化。    

>本项目受到测绘遥感信息工程国家重点实验室开放研究基金的资助。
## 技术栈
* 前端：`D3+jquery`
## 效果展示
本项目在试验中，利用百度地图获取了武汉大学周边140个景点POI的信息（通行时间、受欢迎程度），然后通过本项目所提出的方法生成相应的词云布局，如下图所示：
![图片名称](https://qqq807111690.github.io/web4gis15/wuda.jpg)
上图为生成的中心度词云布局（其中文字颜色代表从武汉大学到周边景点的公共交通出行时间，文字的大小代表景点受欢迎程度）
![图片名称](https://qqq807111690.github.io/web4gis15/three.jpg)
上图为住宿、餐饮、景点三种类型POI的评分的中心度词云(图中红色表示住宿类POI，蓝色表示餐饮类POI，黄色表示景点类POI，符号大小表示兴趣点的评分)
## 运行项目
本项目完全基于前端可视化框架开发完成，可在浏览器直接运行，无需系统环境配置。



