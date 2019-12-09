# 一些补充的资料

## 修改后的SEU开源代码

很多同学来问我说 SEU 的开源代码跑不起来，这其实是因为他们的代码默认的一些逻辑是需要与下位机配合的。我仅仅注释了影响代码跑起来的部分没有做大的改动，这不是我们队实际用的代码。我们队的开源可以看bbs上的这个帖子：**[【哈尔滨工程大学】创梦之翼战队RM19全方位开源汇总贴](https://bbs.robomaster.com/thread-9233-1-1.html) ** 目前队里还没整理好。

下载地址：https://github.com/hejiangda/RM-Archive/raw/master/Robomaster2018-SEU.zip

## 识别数字用的模板

有很多同学问我模板匹配用的是什么样的模板。模板匹配是通过滑窗把图片的每个窗的像素与模板进行匹配。所以模板大小一定要比图片小，而且要被匹配的东西最好与模板一样大小这样模板匹配才会有效。

下载地址：https://github.com/hejiangda/RM-Archive/tree/master/Template