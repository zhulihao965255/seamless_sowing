# seamless_sowing
无缝轮播图实现

git clone https://github.com/zhulihao965255/seamless_sowing.git

支持自动无缝切换轮播

支持鼠标单击切换图片

支持悬浮暂停：即鼠标悬浮在图片上方，轮播可以暂停

请点击[最终实现效果](http://www.zhulihao.cn/seamless_sowing/index.html)
可以改变img文件夹里面的照片，按照原来的图片命名方式进行命名即可。


```
1.首先对要进行的图片进行定位,让其实现横排,让超出的部分使用overflow:hidden隐藏。
2.然后利用setInterval控制left属性的改变从而实现自动控制轮播图的滚动。
3.当鼠标放在照片上时轮播会停止，离开会继续轮播(会有一个标志位辅助实现);
4.点击左或右可以实现照片的向左向右滚动;把鼠标放在数字上时会轮播到指定的第n页。
```
