# 简介
基于electron，用于与用户交互，以及驱动彩印机的项目

## 运行

```shell
$ git clone https://github.com/FHQGitHub262/lbs-printer-frontend.git
$ cd lbs-printer-frontend
$ npm install #安装失败的话，尝试更换npm源或者使用cnpm进行安装
$ npm start
```

## 打包

```shell
$ npx @electron-forge/cli import
$ npm run make
```

打包后的文件在out文件夹下

更多详情见[官方文档](https://www.electronjs.org/docs/tutorial/quick-start)

## 页面

**1. index 主页面** 

操作选择 

**2. 其他页面 /pages**

- QRCode.html 二维码扫描获取图片
- print.html 打印界面
- randomGet.html 随机获取图片
- specification.html 说明页
- telephone.html 联系方式页
- ad.html 广告页