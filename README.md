# Java-Reptile
Java 写的一些简单爬虫例子

### 配置环境
- JDK 1.8.0_121
- jar包：Jsoup, Json
- Win10


### 第一部分音乐下载
1. 通过抓包分析百度云音乐相关请求的api<br>
2. 通过http模拟请求获取api返回信息<br>
3. 解析html数据，求得最终mp3文件路径
4. 保存mp3文件到指定路径

### 第二部分小说爬虫
1. 跟上部分相似抓包获取盗版网站各类请求api<br>
   （正版网站先还不知道如何绕过会员这一关卡）
2. 使用 Jsoup 可以轻松解析html的数据，获取到小说内容