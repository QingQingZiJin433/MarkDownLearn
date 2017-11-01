# demo2
## 链接
### 内嵌式链接
- 外部链接: [链接到百度](http:www.baidu.com)
- 内部链接1，连接到本仓库里面的其他文件 [README.md](./README.md)
- 内部链接2，连接到本文档的其他位置 [代码块](#代码块)
### 引用式链接
* 外部链接: [链接到百度]
* 外部链接: [baidu][链接到百度]，用到别名
* 内部链接1，连接到本仓库里面的其他文件 [README.md]
* 内部链接2，连接到本文档的其他位置 [代码块]

## 图片
- 图片的MarkDown语法  
- ![alt](url text)
  - 外部图片的使用  
    - ![我是图片](https://ss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=3900966785,2864196618&fm=173&s=76A026E000D3BBCC2EB9DD1C03001002&w=640&h=854&img.JPEG "南瓜")

  - 仓库内图片的使用
    - ![内部图片](./img/bd_logo.png "鼠标放上去显示的文字")
- 图片的引用式链接
  - ![我是图片]
  - ![我是图片别名][我是图片]
  - ![引用内部图片]
## 引用
>这是一个引文  

——出自《论语》

### 多次引用
>>> 这是多次引用

## 代码块 
- 行内代码
  - 用来声明变量的代码是 `var a = 10;` 用来打印这个变量的代码是 `console.log(a);` 

- 块级代码
  - ```
    var a = 1;
    console.log(a)
    ```

- 带语法高亮的代码块  
  - ```javascript
    var a = 0;
    console.log(a);
    ```

<!-- 下面是本文档用到的链接和图片 -->
[链接到百度]: http:www.baidu.com
[README.md]: ./README.md
[代码块]: #代码块
[我是图片]: https://ss2.baidu.com/6ONYsjip0QIZ8tyhnq/it/u=3900966785,2864196618&fm=173&s=76A026E000D3BBCC2EB9DD1C03001002&w=640&h=854&img.JPEG "南瓜"
[引用内部图片]: ./img/bd_logo.png "鼠标放上去显示的文字"