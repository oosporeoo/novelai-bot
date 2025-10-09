## [koishi-plugin-novelai](https://bot.novelai.dev)

### 增加/修改功能

- 对LORA标签的支持, 现在可以通过使用尖括号 `<>` 来支持LORA文件使用
- `高级设置` 的输出方式增加了前台发送JSON信息与后台调试输出
- 修复 Forge Webui 使用高清修复时提示 hr_additional_modules 的错误
- 扩展了高清修复的其它几个选项`hrCFG(提示词服从度)` `hrScale(高清倍率)` `hrSteps(高清迭代步数)`
- 增加一组默认的违禁词列表
- 增加使用 `-F` 来临时禁用违禁词的功能
- 增加使用 `-A` 对ADetailer人脸修复插件的支持

### 使用方式
1. 访问 [Releases页面](https://github.com/oosporeoo/novelai-bot/releases/tag/v1.27.0), 下载编译后的 `index.js` 文件
2. 覆盖 Koishi 目录下的 `\node_modules\koishi-plugin-novelai\lib` 内 `index.js` 使用