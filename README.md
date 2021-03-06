# moUI

🍕 面向现代浏览器的 CSS 样式库。

## ✨ 特性

- 原生 CSS 编写
- 深浅色主题与风格定制
- 按需载入国际化文案
- 多框架支持 (**help wanted!**)

## 🎨 本地预览

### 微信小程序


<table>
<tr>
  <td><img src="https://user-images.githubusercontent.com/32428655/72215268-040d7980-354c-11ea-98c1-83efaca51dd7.jpg" width="180" /></td>
  <td colSpan="4">微信扫描小程序码在线预览</td>
</tr>
<tr>
  <td><img src="https://user-images.githubusercontent.com/32428655/71712349-c5870900-2e3f-11ea-8e36-17b878c1af98.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/71712340-c3bd4580-2e3f-11ea-8d69-d2e28b472812.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/71712335-c324af00-2e3f-11ea-9c04-97ebf77a65ae.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/71712348-c5870900-2e3f-11ea-9131-97696b1faa35.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/71712343-c455dc00-2e3f-11ea-9a12-91b021378071.png" width="180" /></td>
</tr>
<tr>
  <td><img src="https://user-images.githubusercontent.com/32428655/72215550-b5151380-354e-11ea-8e53-c7d4e55e38b3.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/72215551-b5151380-354e-11ea-8c61-5839be74da7d.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/72215552-b5adaa00-354e-11ea-9a64-5cb9c7db196b.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/72215553-b6464080-354e-11ea-8cdd-92044ca92708.png" width="180" /></td>
  <td><img src="https://user-images.githubusercontent.com/32428655/72215554-b6464080-354e-11ea-925b-1a663e0e95c6.png" width="180" /></td>
</tr>
</table>

1. Clone 项目到本地，进入 `wechat-minip` 目录，执行命令安装依赖：

```bash
cd wechat-minip && yarn install
# or
cd wechat-minip && npm install
```

2. 在 `wechat-minip` 目录下编译：

```bash
yarn run compile
# or
npm run compile
```

3. 安装并打开[微信开发者工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)，登录后在项目列表页选择导入小程序项目，选中 `wechat-minip` 目录。

> 如果开发者工具提示“不属于项目成员”，删除 `wechat-minip/project.config.json` 中的 `appid` 项再以游客身份重新导入项目。

![import wechat mini-program project](https://user-images.githubusercontent.com/32428655/71554841-94818f80-2a5f-11ea-9340-f0e2252611bc.png)

## 💡 如何贡献

### 注意事项

- 新特性尽可能不要直接修改原样式类，而是在其后追加覆盖，否则可能会影响到组件之间样式的联动效果。
