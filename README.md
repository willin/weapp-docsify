# Docsify 微信小程序

## 在线示例

![qrcode](https://user-images.githubusercontent.com/1890238/38530440-16765852-3c9d-11e8-91dc-3f325b6c44cc.jpeg)

## 开发指南

### 1.Fork 本项目

```bash
# 更换成你的 Git 项目路径
git clone git@github.com:willin/weapp-docsify.git
cd weapp-docsify
# 安装依赖
yarn global add wepy-cli
yarn
yarn dev
# 或者
npm i -g wepy-cli
npm i
npm run dev
```

### 2.开发者工具创建项目

选择该目录下的 `dist` 子目录。

然后修改生成的 `project.config.json`，参考以下，修改三项为 `false`：

```js
"setting": {
  "urlCheck": true,
  "es6": false,
  "postcss": false,
  "minified": false,
  "newFeature": true
}
```

## License

Apache 2.0

通过支付宝捐赠：

![qr](https://cloud.githubusercontent.com/assets/1890238/15489630/fccbb9cc-2193-11e6-9fed-b93c59d6ef37.png)
