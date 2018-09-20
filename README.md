![主题封面][1]

# Typecho主题 - Initial（v1.2.1）

基于Typecho默认主题做一些优化，看不出变化的优化😆。这几天把原版主题翻来覆去的折腾，可以说扫遍了每个文件的每一行代码（幸亏文件不多🤣），算是比较满意了，最近也没什么好分享的，就把这个主题放出来吧。
主题命名为**Initial**，意为“**初**”，算是极极极简风格吧，简约不简单，希望你能喜欢这种很小众的风格。

## 关于更新

2018/9/4：发布第一版
2018/9/8：发布1.1版本
2018/9/12：发布1.2版本
2018/9/17：发布1.2.1版本（增加返回顶部过渡动画，微调ul标签内容样式）

> 1.2版更新内容
> 
> * 优化部分细节
> * 修复一处关于Ajax评论的逻辑性小错误
> * 添加右下角小工具
>  * 返回顶部(1.2.1版添加过渡动画)
>  * 背景音乐

如发现问题请随时[站内反馈](https://www.offodd.com/17.html#comments)🧐

背景音乐这个真是折腾了好久，因为主要是想使用网易的音乐，再加上要尽量做到最轻量，看了几个API框架，直接就放弃了（虽然做完只有不到100KB，但还是觉得太大了），最后找到一个不错的开放API，可惜不支持https😖貌似没办法了。。。
晚上回家思考了一下，制作本主题的初衷就是简约而不简单，既然是要“简约”何不做到极致？好像找到了新的大门🤩

最后确定使用原生HTML5播放器（隐式），后台自定义**一首**你最最喜欢的音乐循环播放（后台可给音乐设置一个合适的音量），仅使用一个按钮来集成**显示播放状态**、**播放控制**、~~类Ajax加载~~（由于部分移动端浏览器的特殊内置设置问题，此项已经取消；其实通过监听触控可以解决，但是还是算了吧，不过放心，仍然不会影响我们宝贵的页面加载速度。）*显示播放和暂停状态由纯CSS实现；播放和暂停控制由原生JS实现。*虽然没有使用框架那么强大的功能和兼容性，但觉得非常符合本主题初衷。

> 1.1版更新内容
> 
> * 全站Pjax + ajax评论
> * 二维码打赏

## 关于外观

主题预览就是[本站](https://www.offodd.com/)
看上去几乎和原版一模一样，尽量保持原生态，当然不和谐的地方也有优化，大半的CSS都已经重写。

## 关于功能

没有使用任何JS、框架，所以没添加什么高深的功能，也是为了**Initial**，够用就行，不是吗？
*下一版将要加入pjax和ajax，要用到jp了，不过无jp的纯净版也会继续更新优化。（pjax和ajax提供开关，其实关闭后就还是纯净版😁）*

> 目前已添加的小功能：
> * 重新优化移动端自适应
> * 添加一套归档模板（模板也是使用原版风格，无特别美化）
> * Favicon 和 Apple Touch Icon 地址
> * 支持将CSS文件链接替换为cdn地址
> * DNS预获取（公共资源替换为BootCDN来源）
> * 自定义ICP备案号
> * 底部自定义内容（统计代码等）
> * 全站Pjax + ajax评论
> * 二维码打赏
> * 右下角小工具
>  * 返回顶部
>  * 背景音乐

**以上功能均支持手动开启或关闭，喜欢极简的朋友可以关闭Pjax和右下角小工具，恢复极简体验（不加载任何JQ和JS）**

嘴巴比较笨，不太理解的话可以试用一下😅

![设置界面预览][2]
<br>▲设置界面预览

## 关于使用

下载主题包并解压，把解压出来的文件夹改名为“initial”，将文件夹上传至网站文件主题目录下，网站后台启用主题即可。
第一次把公开主题，不知道是否适合大众的胃口，如果使用过程中有什么疑问或建议，可以随时[联系我](https://www.offodd.com/17.html#comments)。

  [1]: https://www.offodd.com/usr/uploads/2018/09/111355748.png
  [2]: https://www.offodd.com/usr/uploads/2018/09/902666254.jpg