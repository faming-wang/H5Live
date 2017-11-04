为了提升品牌影响的影响力和推广产品，H5直播间已经成为了一款直播产品的必备要素。在网络直播盛行的这个风口浪尖，直播产品的模式越来越成熟，一个直播间所需要的元素和交互已经形成了稳定的模式。于是，你没理由完全要自己手动搭建一个H5直播间，因为H5Live提供了一套成熟稳定的H5直播间方案：

1. 组件化、配置化搭建，5分钟快速上手；
2. 涵盖公屏、大礼物、小礼物、弹幕、点赞等功能模块；
3. 配备高性能的礼物动画方案；

----

![h5live](https://user-images.githubusercontent.com/1295348/31772948-c3eb733e-b4a6-11e7-83a8-2fbce55a62f8.png)


## 入门

为了加快开发效率，推荐你使用开箱即用的[LegoFlow](https://legoflow.com/)进行开发。当然，你也可以自己配置webpack进行开发，只需要支持ES6编译和SASS loader即可。

### 目录结构

````
js/
├── component //组件
|   ├── palyer
|   ├── ...
│   └── top-bar
├── lib //第三方库
├── public //公共，例如api，全局配置，工具等
└── main.js //主入口
````

````html
<script src="https://s1.yy.com/ued_web_static/lib/anti-hijack/index.js"></script>
<script>new LegoAntiHijack();</script>
````

````html
<script>
new LegoAntiHijack({
    whiteList: ['xxx.yy.com']
});
</script>
````

## Issues

如有使用问题或建议，欢迎提issues

