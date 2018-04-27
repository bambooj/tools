
# Sublime Text 3 实现实时预览

## 一、插件安装

### 1.1 安装Markdown Preview
Markdown Preview插件可以打开浏览器，预览编写的md文件；

按下ctrl + shift + P 快速打开菜单，键入“mp”；

### 1.2 Markdown Editing
Markdown Editing 是Markdown编辑器和语法高亮支持；

### 1.3 Auto-Save 
Auto-Save 可以自定义自动保存功能；

## 二、配置

### 2.1 自动刷新配置

在所编辑的md文件末尾加上自动刷新代码，0.1s比较合适；

```
<meta http-equiv="refresh" content="0.1">
```

### 2.2 配置Mardown Preview

配置路径
> Preferences -> Package Settings -> Markdown Preview -> Setting User

配置内容
> "enable_auto_reload": true

结果如下：

```
{
 "enable_mathjax": true,
 "enable_highlight": true,
  "enable_autoreload": true
}
```

注：只需在Settings-User里面配置即可,因为Settings-default里面无法修改；但是配置项可以参考default里面的配置；

### 2.3 配置Auto-Save

配置路径
> Preferences -> Package Settings -> Auto Save -> Setting User

配置内容
> "auto_save_delay_in_seconds": 0.15

结果如下：
```
{
    "auto_save_delay_in_seconds": 0.15  
}
```

## 三、使用

1. 按下ctrl+shift+P打开快速菜单，键入’mp’ 

![https://img-blog.csdn.net/20161026023550558](https://img-blog.csdn.net/20161026023550558)

2. 按下ctrl+shift+P打开快速菜单，键入"auto"

![https://img-blog.csdn.net/20161026023931422](https://img-blog.csdn.net/20161026023931422)

<meta http-equiv="refresh" content="0.1">
