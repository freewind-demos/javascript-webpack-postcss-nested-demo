JavaScript PostCSS Demo
=======================

PostCSS是一个对CSS进行各种转换的工具。

通过各种插件，我们可以对css文件进行各种花样的转换。

本Demo用到的是`autoprefixer`插件，可以在让我们标准（但可能还没有被浏览器支持）的css属性，然后由该插件给它加上各种前缀，让它被各浏览器使用各自的方言来支持。

```
npm install
npm run demo
```

它将会在`build`目录下生成经过转换之后的`hello.css`。
