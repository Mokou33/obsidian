```shell
git init  # 初始化项目

git add . # 将项目的所有文件添加到仓库中

git commit -m '提交的说明注释'  # 将文件 commit 到仓库

git remote add origin https://github.com/<id>/< 项目仓库 >  # 将本地仓库关联到 github

git pull origin master   # 将远程仓库 同步 本地

git push -u origin master # 将本地文件上传到 github
这一步可能会报错
* git错误 error: failed to push some refs to 'https://github.com/...
解决办法：
git pull --rebase or
```

前端文档

`https://malun666.github.io/aicoder_vip_doc`

VScode 插件

```css
Atom One Dark Theme	# 主题
Dracula Official # 主题
Live Server	 # 浏览器实时刷新
open in browser # 编辑器中打开浏览器
beautify # 格式化代码工具
Bracket Pair Colorizer # 用于着色匹配括号
Rainbow Brackets # 为圆括号，方括号和大括号提供彩虹色。这对于Lisp或Clojure程序员，当然还有JavaScript和其他程序员特别有用。

Import Cost # 对引入的计算大小
Path Intellisense # 可自动填充文件名。
Npm Intellisense # 用于在 import 语句中自动填充 npm 模块
Project Manager # 它可以帮助您轻松访问项目，无论它们位于何处。不要再错过那些重要的项目了。您可以定义自己的收藏项目，或选择自动检测VSCode项目，Git，Mercurial和SVN存储库或任何文件夹。
Atuo Rename Tag # 修改 html 标签，自动帮你完成头部和尾部闭合标签的同步修改

代码类
HTML Snippets # 完整的HTML代码提示，包括HTML5
HTML CSS Support #  在 html 标签上写class 智能提示css样式
jQuery Code Snippets #  jQuery代码提示超过130个用于JavaScript代码的jQuery代码片段。需键入字母'jq'即可获得所有可用jQuery代码片段的列表。
HTMLHint  # html代码检测，支持html5

vue
vetur   　　# 语法高亮、智能感知、Emmet等
VueHelper  #　snippet代码片段
ESLint    　#　将ESLint JavaScript集成到VS代码中。
prettier    #代码规范性插件
vue vscode snippets  # vue组件模板

JavaScript(ES6) code snippets #  ES6语法智能提示以及快速输入，除js外还支持.ts，.jsx，.tsx，.html，.vue，省去了配置其支持各种包含js代码文件的时间

```

