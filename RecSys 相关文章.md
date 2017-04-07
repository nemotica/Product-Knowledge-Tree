# 推荐系统相关阅读
- 最后更新：20170407

## 目录
- 评测指标
- 推荐策略 & 算法
- 冷启动
- 例子

#### 评测指标
* [类似今日头条这样的个性化推荐网站怎么评价推荐质量的优劣？](https://www.zhihu.com/question/26990692)
* [个性化推荐产品的核心指标有哪些？](http://www.woshipm.com/pmd/577849.html)
  * pv点击率、uv点击率、曝光点击率、uv转化率、人均点击次数
  * 留存率、停留时长、播放完成率
  
#### 综述
* [[IBM导论类文章] 探索推荐引擎内部的秘密，第 1 部分: 推荐引擎初探](https://www.ibm.com/developerworks/cn/web/1103_zhaoct_recommstudy1/index.html) 
* [[微信公号文章] 如何思考个性化推荐的? by 36大数据](https://mp.weixin.qq.com/s?__biz=MjM5MTYwMjI3Mw==&mid=2652092420&idx=1&sn=257cb12a974a3a462a3ad24b28352adc&chksm=bd541b0a8a23921cd0232e25c932a19b8b899dafd8c4c9357772340385de6921cb279ee0748a&scene=0&key=c4bc7a76474952388236444702369a08af0f266b82e99759e147d5cea32c0f4dc71423374c986c6b5022f1e7be3ceeb3c2bc878d13dc205f2edee0a1ecb6f75f4cf4e9e4e524d015511c14a4d67860bf&ascene=0&uin=NzY4MDE2OTIw&devicetype=iMac+MacBookPro11%2C4+OSX+OSX+10.12.2+build(16C67)&version=12010210&nettype=WIFI&fontScale=100&pass_ticket=%2FPWuXFxipPjOG%2FSDPQbQ4F6Qr1IQTEOvfsimcnRbDzfvbpvDiYxpDN%2ByOqYDtTt9)

* [[阿稳博文] 少数人的智慧(The Wisdom of the Few)  谷大看到paper，写了博客，阿稳看了blog又发了一篇blog ](http://blog.sciencenet.cn/blog-64458-372804.html)
* [[经验分享]  Xavier Amatriain在ACM Recsys上的推荐系统经验分享 ](http://www.pmcaff.com/article/index/492418935747712?from=search)
* [信息来源] Google Blog Search的关键字搜索，delicious的tag，twitter的#hashtag，微博的话题订阅； 
* [kaggle] 类Netflix算法比赛，有数据集，可以实现 
* [[知乎王科] 博客链接 ](http://www.wangke.me/?p=103)
* [[阮一峰的blog] 知乎发现的“今日最热”是怎么来的？](https://www.zhihu.com/question/22898893)
* [[知乎gqyjlu@搜狗产品经理] 如何做好推荐算法  - 如何做好搜索算法 ](https://www.zhihu.com/question/20558659/answer/19351567)
* [[微博推荐团队博客] 链接 ](http://www.wbrecom.com)
* [[推荐算法综述（一）@InfoQ] 翻译自Building Recommenders  -  ](http://www.infoq.com/cn/articles/recommendation-algorithm-overview-part01)
* [[寻路推荐 理念篇] 博客链接 ](http://www.52cs.org/?p=10)

#### 冷启动
[[知乎问答@刘彦彬] 有哪些解决推荐系统中冷启动的思路和方法？ ](https://www.zhihu.com/question/19843390/answer/40454433)
* 通过不同纬度获取用户基本特征，操作习惯，进行粗粒度推荐；
* 1 利用其他平台数据（第三方注册）；
* 2 利用用户手机等兴趣偏好（Android获取安装其他应用）；
* 3 让用户自己选择；例子：网易云音乐的FM的冷启动；

#### 例子 
* [[PMCAFF@刘彦彬] QQ音乐是如何思考个性化推荐的？ ](http://www.pmcaff.com/article/index/560816754431104?from=search) 

