# ocean-weather

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


# 在线demo
[在线demo](https://danwild.github.io/leaflet-velocity/)

# step1: 在leaflet上绘制canvas图层
[在leaflet上绘制canvas图](https://github.com/Sumbera/gLayers.Leaflet)

# step2: 完整的leaflet-wind版本
[完整的leaflet-wind版本](https://github.com/danwild/leaflet-velocity)

# 理论依据

* [数据来源](http://nomads.ncep.noaa.gov/)
* [grib](http://www.cpc.ncep.noaa.gov/products/wesley/reading_grib.html)
* [数据转换](https://github.com/cambecc/grib2json)
* [双线性插值算法](https://github.com/cambecc/earth)


20170927

https://www.windy.com
https://github.com/windyty/API
1、全球跨180度展示  worldCopyJump:true
2、风的动态效果
3、跟宝船网类似
4、线光滑  http://turfjs.org/docs/#bezier
5、文字效果
6、等值面生成
