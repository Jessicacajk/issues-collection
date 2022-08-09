# issues-collection
一些技术问题的收集
## CSS
### 1. font-weight:600 
在IOS上是粗体，在Android端不生效，建议直接用font-weight:bold

## 组件库
### 1. 用到的包
* concurrently：让脚本同步进行， "dev": "concurrently \"pnpm docs:dev\"  \"pnpm example:dev\""。
* fs-extra：fs的扩展包，读写文件的node包，用来创建模板文件。
* inquirer: node包，命令行交互工具。
* path：处理文件路径的。
* chalk：处理终端字符串样式。
