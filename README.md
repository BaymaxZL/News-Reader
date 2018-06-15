#操作说明书
##这是基于安卓的新闻阅读App
* 整体项目基于 MVP + RxJava + Retrofit
* 通过 Retrofit 实现了无网缓存
* 基于 MVP 模式对 Activity 和 Fragment 封装了两个基类，同样适用于非 MVP 的实现。
* 运用 RecyclerView 加载了多种复杂布局
* 用到了一些很棒的第三方库

###主界面
* 汇集了知乎日报，干货集中营，以及好奇心日报，三种不同风格的阅读体验
* 知乎日报 API 取自[ZhihuDailyPurify](https://github.com/izzyleung/ZhihuDailyPurify/wiki/%E7%9F%A5%E4%B9%8E%E6%97%A5%E6%8A%A5-API-%E5%88%86%E6%9E%90)
* 干货集中营 API 取自[gank.io](http://gank.io/api)
![](/screenshots/Screenshot_1529056110.png)
![](/screenshots/Screenshot_1529056117.png)
![](/screenshots/Screenshot_1529056120.png)
* 轮播图部分可以自动轮播，也可以通过左右滑动切换新闻
* 在主体部分可以通过左右滑动切换新闻来源，也可以直接点击知乎，干货，满足你的好奇心的标签进行切换
* 每种阅读界面均可以通过下拉进行刷新，上拉加载更多
* 右上角菜单提供github今日热门
![](/screenshots/Screenshot_1529056038.png)
###新闻阅读界面
* 点击新闻标题可以跳转到该新闻的详情页面
![](/screenshots/Screenshot_1529058065.png)
* 知乎的新闻详情页面可以下拉加载更多，干货集中营主要提供图片浏览，可以点击保存图片将图片保存在本地
![](/screenshots/Screenshot_1529058152.png)