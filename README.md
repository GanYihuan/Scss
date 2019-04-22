# Scss

## 大纲

![大纲](https://i.loli.net/2019/04/22/5cbd11a8895cb.png)

## 环境

```node
cnpm i node-sass sass-loader -D
```

## 编译

### 单个文件编译

```node
node-sass --watch <源文件> <目标文件>
```

### 实时编译

```node
sass --watch sass/bootstrap.scss:css/bootstrap.css
```

### 多文件编译

- 项目中“sass”文件夹中所有“.scss”(“.sass”)文件编译成“.css”文件，并且将这些 CSS 文件都放在项目中“css”文件夹中
- 点击底部栏 `Live Sass Compiler 插件` `Watch Sass`

```node
sass --watch scss/:css/
```

## 风格

1. 嵌套输出方式 nested
2. 展开输出方式 expanded
3. 紧凑输出方式 compact
4. 压缩输出方式 compressed

```node
sass --watch test.scss:test.css --style nested
```
