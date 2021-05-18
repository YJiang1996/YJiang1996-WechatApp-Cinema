# 微信小程序电影订票

​	本小程序是基于云开发技术实现项目开发的：

## 云开发的优势

​		开发者可以使用云开发开发微信小程序、小游戏，无需搭建服务器，即可使用云端能力。
​		云开发为开发者提供完整的原生云端支持和微信服务支持，弱化后端和运维概念，无需搭建服务器，使用平台提供的 API 进行核心业务开发，即可实现快速上线和迭代，同时这一能力，同开发者已经使用的云服务相互兼容，并不互斥。

## [微信官方文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

## 项目目录布局

- cloudfunctions:指定本地目录作为云函数的本地目录；

- miniprogram目录下：

  images 目录存放图片；
  pages目录中除admin外均为前台，admin属于后台；
  utils目录存放一些API文件；

- app.js、app.json、app.wxss为全局文件

- project.config.json为项目配置文件

## 主要功能

### 前台主要功能

1. 电影：展示了所有电影也能实现搜索
2. 电影详情：主要是显示电影详情以及想看&收藏功能
3. 影院：获取微信定位，展示附近影院也能实现搜索
4. 购票：查看附近影院上映的电影及场次信息
5. 订单：查看自己的订单列表
6. 想看的电影：查看自己的想看列表
7. 收藏的电影：查看自己的收藏列表
8. 意见或建议：用户以匿名方式向超级管理员提出小程序的不足或是提出建议，保证用户较好的体验

### 后台主要功能

1. 新增电影：新增电影到对应影院

2. 新增场次：由新增电影带来的必须新增电影播放场次

3. 下架电影：从影院中下架电影

   

## 如有任何改善优化建议，可邮件联系

本人邮箱 243486105@qq.com


### V2.0（2021年4月20号）更新一些功能模块 (官方停用getUserInfo组件，改用getUserProfile)


### 如果觉得对开发有帮助的话，可以打赏支持下我，我会努力更新下去的（虽然现在已经转行了


<table>
    <tr>
        <td ><center><img style="width:400px;height:400px" src="https://6679-fyj19961225-03d3fd-1258656498.tcb.qcloud.la/images/qrcode.png"><p>微信</p></center></td>
        <td ><center><img style="width:400px;height:400px" src="https://6679-fyj19961225-03d3fd-1258656498.tcb.qcloud.la/images/qrcode2.png"><p>支付宝</p></center></td>
    </tr>
</table>

## <font color='red'>感谢大佬巨款</font>