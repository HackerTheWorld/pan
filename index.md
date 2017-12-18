## HackerTheWorld的个人主页

主要接收java web项目，完成项目前后端，android项目，服务器端编程。完成4个项目均以上线。现在学习python神经网络方面的学习。以上项目都在linux平台开发。
C系列语言有接触。

### 扫码APP

为某公司开发的方便仓库管理人员对货物的出入库的盘点。

```markdown
通过扫码方式完成货物出入库的记录

- 后端采用php方法实现对mysql数据库的操作。
- android端采用广播方式实现调用扫码接口，每一个action都保证彻底关闭，方式防止应广播带来的数据重复发送。
- android采用Thread的方式来调用远程网络接口。
- hanlder用来实现主线程和进程之间的渲染。
- android采用list[map]格式的json来实现前后端数据的通信。

```

[github源码地址](https://github.com/HackerTheWorld/scanEQInfo)

### 基于java的网络爬虫

定向网络爬虫

```markdown
用java完成的定向聚焦网络爬虫

- 从出对列中取出url，采用httpclient下载网页。并为每一个爬虫开放一个线程。
- 将下载的页面转换成node数据格式，提取每一个href，src标签中的地址。
- 采用md5压缩算法将访问过的地址放入出队列，并根据出入队列判断是否访问过。
- 在提取完href和src后生成doom树，作为模板。
- 将提取的数据存放入bekerly DB。

```
[github源码地址](https://github.com/HackerTheWorld/Spader)

### 基于java的word文档操作转换功能

采用apache开发的二次编程

```markdown
采用java基于apache工具包的二次开发

- filecopy.doc()用于获取word文档中的表格的内容
- 根据文件的后缀名判断是否为doc或者docx文件。
- WordToHtmlAction.Word2007ToHtml()实现对docx转换为html文件并在网页上直接展示
- WordToHtmlAction.Word2003ToHtml()。。。。

```
[github源码地址](https://github.com/HackerTheWorld/word)

### 基于Spring的websocket实现

```
[github源码地址](https://github.com/HackerTheWorld/word)
