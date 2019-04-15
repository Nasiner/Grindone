# 小程序微商城

## 项目描述
- 基于微信小程序的小程序商城买家端，采用`wepy`框架开发；
- 项目实现了基本的商城功能；
- 目前后端数据是基于`easy-mock`的随机模拟数据，且页面只开放了少部分功能；
- 目前只对接了部分接口，如果接口报错404，说明该接口还尚未配置Mock数据，后续会继续完善。
- 有需要模拟数据界面，可以提ISSUE；

> 小程序商家管理端：https://github.com/coolhwm/leshare-seller-wepy

## 部分截图
![预览1](http://img.leshare.shop/github/customer/preivew-001.jpg)
![预览2](http://img.leshare.shop/github/customer/preivew-002.jpg)
![预览2](http://img.leshare.shop/github/customer/preivew-003.jpg)

## 部署说明

### 安装环境
```
# 安装（更新） wepy 命令行工具。
cnpm install wepy-cli -g
# 安装依赖包
cnpm install
# 开发实时编译。
npm run dev
```

### 小程序工具
- 使用微信开发者工具-->添加项目，选择dist目录；
- 可以使用体验APPID；
- 关闭ES6转ES5；
- 关闭上传代码时样式自动补；
- 关闭代码压缩上传；
- 打开不校验合法域名；

> [WePY开发文档参考](https://tencent.github.io/wepy/)


## 功能清单

## License
MIT
