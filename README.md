# reader
免费小说阅读App

参考项目

1.android-showcase 模块化的mvvm开发 [android-showcase](https://github.com/igorwojda/android-showcase)

2.Pokedex 单项目 mvvm，flow [Pokedex](https://github.com/skydoves/Pokedex)

3.NovelReader 基于"任阅"的改进追书App [NovelReader](https://github.com/newbiechen1024/NovelReader)

4.FreeNovel 基于kotlin的免费Android小说应用[FreeNovel](https://github.com/lxygithub/FreeNovel) 

5.OKBook kotlin + 协程 + MVVM 模式来编写的看小说APP [OKBook](https://gitee.com/xcode_xiao/OKBook)

# 应用展示

![](https://github.com/woodwen/reader/tree/main/screenshot/1.jpeg)
![](https://github.com/woodwen/reader/tree/main/screenshot/2.jpeg)
![](https://github.com/woodwen/reader/tree/main/screenshot/3.jpeg)
![](https://github.com/woodwen/reader/tree/main/screenshot/4.jpeg)
![](https://github.com/woodwen/reader/tree/main/screenshot/5.jpeg)
![](https://github.com/woodwen/reader/tree/main/screenshot/6.jpeg)


# 应用简介

小说阅读器（模块化开发/单项目开发，基于Kotlin+MVVM+Kodein/Hilt+Retrofit+Jsoup+Moshi+Coroutines+Flow+Jetpack+Coil+Room+Mockk等架构实现），用kotlin重写了“任阅”的阅读模块代码，优化，代码逻辑，降低内存使用率。

目前已有功能：

1.书城

  * 支持书城切换（目前支持，全文阅读网，笔趣阁）。
  * 支持小说分类切换。
  * 支持按书名，作者搜索小说。
  * 支持查看小说简介。
  * 支持小说订阅
  * 支持直接在线阅读
  
2.书架
  
   * 支持取消订阅
   * 支持搜索书架
   * 支持订阅本地书籍（目前只支持.txt）
   * 支持本地阅读
    
3.个人配置
  
  * 清理缓存
  * 跳转github
  
4.阅读

  * 目录（小说目录）
  * 亮度（设置阅读器亮度，日/夜模式）
  * 缓存（下载小说到本地）
  * 设置（字体，字号，翻页模式，背景图片）

准备加入但是目前还没的功能：

	1.隐藏书城
	2.尝试支持厚墨源
	3.书城不再是写死的方式，而是类似于厚墨的安装方式
	4.支持语音朗读

**注: 该项目不定时维护更新，如有侵权的地方，请告知小弟，立马删除**

# 以下为框架相关（开辟了两个分支，一个是单项目的，一个是模块化的）

   [单模块版本](https://github.com/woodwen/reader/tree/dev-single)

   [多模块版本](https://github.com/woodwen/reader/tree/dev-multiple)
