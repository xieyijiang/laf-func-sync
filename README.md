# laf-func-sync
一个管理Laf云函数本地缓存的插件

## 基本功能
- 查看云函数是否在本地有缓存
- 查看本地缓存与云端代码的diff信息
- 同步代码(删除本地缓存并刷新网页，使编辑器中的代码与云端一致)

## 如何使用
假设你已经安装了油猴插件：
- 前往 [安装地址](https://greasyfork.org/zh-CN/scripts/464731-laf-func-sync){:target="_blank"} 一键安装
- 如果安装地址失效，你可以将 `tampermonkey.js` 中的内容替换到油猴编辑器中保存成一个新的脚本，就可以使用了

## 更新日志
### v0.1.3 (2023-04-25)
- 优化：表头显示缓存函数数量

### v0.1.2 (2023-04-25)
- 调整：确认同步后，调用 `location.replace()` 跳转到同步后的函数页面，替换之前的 `location.reload()`
- 调整：按钮位置向右下角位移，避免遮挡新的底部状态栏信息

### v0.1.1 (2023-04-24)
- 优化：删除冗余代码