# 插件列表

### CODE SETTINGS SYNC UPLOAD SUMMARY
### Version: 3.2.0
``` bash
GitHub Gist Type: Secret
```
### Restarting Visual Studio Code may be required to apply color and file icon theme.
``` bash
Files Uploaded:
  extensions.json > extensions.json
  keybindings.json > keybindings.json
  locale.json > locale.json
  settings.json > settings.json
  vsicons.settings.json > vsicons.settings.json

Extensions Ignored:
  No extensions ignored.

Extensions Removed:
  No extensions removed.

Extensions Added:
  aessoft-class-autocomplete v0.1.0
  auto-close-tag v0.5.6
  auto-rename-tag v0.0.15
  beautify v1.4.7
  Bookmarks v9.1.0
  bracket-pair-colorizer v1.0.60
  code-settings-sync v3.2.0
  cssrem v0.0.7
  eva-theme v0.6.0
  HTMLHint v0.5.0
  jquerysnippets v0.0.1
  language-stylus v1.10.0
  material-icon-theme v3.6.0
  minapp-vscode v1.9.0
  mpvue-snippets v1.2.1
  open-in-browser v2.0.0
  path-intellisense v1.4.2
  prettier-vscode v1.6.1
  project-manager v9.0.1
  Scss2CssPlus v0.0.5
  sublime-keybindings v4.0.0
  vetur v0.13.0
  vscode-eslint v1.7.0
  vscode-fileheader v0.0.2
  vscode-filesize v2.1.1
  vscode-html-css v0.2.0
  vscode-javascript-snippet-pack v0.1.5
  vscode-language-pack-zh-hans v1.28.2
  vscode-npm-script v0.3.5
  vscode-scss v0.6.2
  vue-peek v1.0.2
  vue-snippets v0.1.9
```

# 食用方法

> 涵盖主题，图标，字体，代码上色，代码片段，自动格式化，自动补全等

> 过程中因为编辑器性能原因删掉过一部分插件

> 推荐写Vue、小程序、JQ、Stylus等重度患者推荐使用
``` bash
1、Settings Sync是vscode中同步设置和安装插件的小工具，在扩展商店中搜索并安装它 
2、登陆Github>Your profile> settings>Developer settings>personal access tokens>generate new token，输入名称，勾选Gist，提交 
3、保存Github Access Token 
4、打开vscode，Ctrl+Shift+P打开命令框，输入sync，找到update/upload settings，输入Token，上传成功后会返回Gist ID，保存此Gist ID. 
5、若需在其他机器上DownLoad插件的话，同样，Ctrl+Shift+P打开命令框，输入sync，找到Download settings，会跳转到Github的Token编辑界面，点Edit，regenerate token，保存新生成的token，在vscode命令框中输入此Token，回车，再输入之前的Gist ID，即可同步插件和设置。
```
> 具体步骤可以前往 https://www.cnblogs.com/kenz520/p/7416836.html 查看

Done.

