# leaflet.od
迁徙图数据可视化,用于人口迁移，物流信息展示   
     
##supported browsers
Internet Explorer 10+     
Google Chrome     
Safari    
Firefox        

##Demo online   
A demo is available on the Github Pages webpage for leaflet.od [Check out demo!](https://react-map.github.io/leaflet.od/).

##Usage     
1.添加leaflet.od源代码到页面
```html
<script src="./dist/leaflet.od.js"></script>
```    
2.创建一个odLayer
```js
var odlayer = new L.od({
    map: map,
    data: JSON.parse(data)
})
```     
3.更新数据或者发送新的数据到odLayer
```js
odlayer.setData(newData);
```   
4.隐藏odLayer图层       
```js
odlayer.hide();
```   
5.显示odlayer图层       
```js
odlayer.show();
```   
6.暂停动画效果   
```js
odlayer.pause();
```   
7.播放动画效果     
```js
odlayer.play();
```   
8.彻底展示odLayer图层     
```js
odlayer.destroy();
```   
## License   
MIT.    