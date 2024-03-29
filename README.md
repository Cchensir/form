![image](https://ae01.alicdn.com/kf/U51bfb661aba945b48a4c71774421d414C.gif)
## 简介
Element UI表单设计及代码生成器，可将生成的代码直接运行在基于Element的vue项目中；也可导出JSON表单，使用配套的解析器将JSON解析成真实的表单。 

## 文档
- [el-dialog的封装与调用](https://github.com/JakHuang/form-generator/wiki/el-dialog%E7%9A%84%E5%B0%81%E8%A3%85%E4%B8%8E%E8%B0%83%E7%94%A8)
- [项目主要结构分析](https://github.com/JakHuang/form-generator/wiki/%E9%A1%B9%E7%9B%AE%E4%B8%BB%E8%A6%81%E7%BB%93%E6%9E%84%E5%88%86%E6%9E%90)
- [【常见问题】如何以npm的方式集成monaco编辑器](https://github.com/JakHuang/monaco-vue-demo)
- 系列教程：
[《表单设计器 · 开发教程》](https://github.com/JakHuang/form-generator/issues/30)
[《表单解析器 · 开发教程》](https://github.com/JakHuang/form-generator/issues/32)
[《vue代码生成器 · 开发教程》](https://github.com/JakHuang/form-generator/issues/31)
[《vue代码预览器 · 开发教程》](https://github.com/JakHuang/form-generator/issues/33)
- [JSON表单参数对照表](https://github.com/JakHuang/form-generator/issues/46)

## JSON解析器
将保存在数据库中的JSON表单，解析成真实的表单  
[查看在线示例](https://mrhj.gitee.io/form-generator/#/parser) 
```
// 安装
npm i form-gen-parser
```
[更多信息](https://github.com/JakHuang/form-generator/tree/dev/src/components/parser) 

## vscode插件
帮助使用element UI的开发者完成基本的表单代码搭建任务，减少重复的劳动。  
vscode-plugin分支配套插件为：[form-generator-plugin](https://github.com/JakHuang/form-generator-plugin)；  
使用插件可右键打开设计器，直接将代码保存到工程中。  
安装插件请在vscode中搜索：
>jakHuang   
或  
Form Generator Plugin
## 运行
- 确保已经安装node.js 10+
- 首次下载项目后，安装项目依赖：
```
yarn
```
或
```
npm install
```
- 本地开发
```
npm run dev
```
- 构建
```
npm run build
```
