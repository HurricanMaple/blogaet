---
layout: post

date: 2022-12-13

title: 飓枫自建网易云音乐 api （一）

author: 飓枫

pin: true
---



飓枫网易云api介绍
<!-- more -->

本 api 为公益项目，使用 vercel 部署相应速度快，24 小时运行，不必担心会跑路
可解析 VIP 音乐使用第三方下载器即可下载，登录信息安全：本站不会储存任何一个用户的 cookie 和账号！本 api 基于 GitHub 开源项目进行修改完善。本 api 可以选择音乐音质（免费）等等…
api 官网：https://xyz.jywl.fun/

发现 bug 请及时反馈给邮箱：fieeple@petalmail.com
如有任何问题可反馈到下方评论区

## 功能一览

{% folding cyan open::功能查看 %}



登录
刷新登录
发送验证码
校验验证码
注册(修改密码)
获取用户信息 ， 歌单，收藏，mv， dj 数量
获取用户歌单
获取用户电台
获取用户关注列表
获取用户粉丝列表
获取用户动态
获取用户播放记录
获取精品歌单
获取歌单详情
搜索
搜索建议
获取歌词
歌曲评论
收藏单曲到歌单
专辑评论
歌单评论
MV 评论
电台节目评论
旗帜
获取歌曲详情
获取专辑内容
获取歌手单曲
获取歌手 mv
获取歌手专辑
获取歌手描述
获取相似歌手
获取相似歌单
相似 mv
获取相似音乐
获取最近 5 个听了这首歌的用户
获取每日推荐歌单
获取每日推荐歌曲
私人 FM
签到
喜欢音乐
垃圾桶
歌单 ( 网友精选碟 )
新碟上架
热门歌手
最新 mv
推荐 MV
推荐歌单
推荐新音乐
推荐电台
推荐节目
独家放送
MV 排行
获取 mv 数据
播放 MV/视频
排行榜
歌手榜
云盘
电台 - 推荐
电台 - 分类
电台 - 分类推荐
电台 - 订阅
电台 - 详情
电台 - 节目
给评论点赞
获取动态
热搜列表(简略)
发送私信
发送私信歌单
新建歌单
收藏/取消收藏歌单
歌单分类
收藏的歌手列表
订阅的电台列表
相关歌单推荐
付费精选接口
音乐是否可用检查接口
登录状态
获取视频播放地址
发送/删除评论
热门评论
视频评论
退出登录
所有榜单
所有榜单内容摘要
收藏视频
收藏 MV
视频详情
相关视频
关注用户
新歌速递
喜欢音乐列表(无序)
收藏的 MV 列表
获取最新专辑
听歌打卡
获取视频标签/分类下的视频
已收藏专辑列表
获取动态评论
歌单收藏者列表
云盘歌曲删除
热门话题
电台 - 推荐类型
电台 - 非热门类型
电台 - 今日优选
心动模式/智能播放
转发动态
删除动态
分享歌曲、歌单、MV、电台、电台节目到动态
通知-私信
通知-评论
通知-@我
通知-通知
设置
云盘数据详情
私信内容
我的数字专辑
批处理批量请求接口
获取视频标签列表
全部 mv
网易出品 MV
收藏/取消收藏专辑
专辑动态信息
热搜列表(详细)
更换绑定手机
检测手机号码是否已注册
初始化昵称
更新歌单描述
更新歌单名
更新歌单标签
默认搜索关键词
删除歌单
电台横幅
用户电台
热门电台
电台 - 节目详情
电台 - 节目榜
电台 - 新晋电台榜/热门电台榜
类别热门电台
云村热评(官方下架,暂不能用)
电台 24 小时节目榜
电台 24 小时主播榜
电台最热主播榜
电台主播新人榜
电台付费精品榜
歌手热门 50 首歌曲
购买数字专辑
获取 mv 点赞转发评论数数据
获取视频点赞转发评论数数据
调整歌单顺序
调整歌曲顺序
独家放送列表
获取推荐视频
获取视频分类列表
获取全部视频列表接口
获取历史日推可用日期列表
获取历史日推详细数据
国家编码列表
首页-发现
首页-发现-圆形图标入口列表
全部新碟
数字专辑-新碟上架
数字专辑&数字单曲-榜单
数字专辑-语种风格馆
数字专辑详情
更新头像
歌单封面上传
楼层评论
歌手全部歌曲
精品歌单标签列表
用户等级信息
电台个性推荐
用户绑定信息
用户绑定手机
新版评论
点赞过的视频
收藏视频到视频歌单
删除视频歌单里的视频
最近播放的视频
音乐日历
电台订阅者列表
云贝签到信息
云贝签到
云贝所有任务
云贝 todo 任务
云贝今日签到信息
云贝完成任务
云贝收入
云贝支出
云贝账户信息
账号信息
最近联系人
私信音乐
抱一抱评论
评论抱一抱列表
收藏的专栏
关注歌手新歌
关注歌手新 MV
歌手详情
云盘上传
二维码登录
话题详情
话题详情热门动态
歌单详情动态
绑定手机
一起听状态
用户历史评论
云盘歌曲信息匹配纠正
云贝推歌
云贝推歌历史记录
已购单曲
获取 mlog 播放地址
将 mlog id 转为视频 id
VIP 成长值
VIP 成长值获取记录
VIP 任务
领取 VIP 成长值
歌手粉丝
数字专辑详情
数字专辑销量
音乐人数据概况
音乐人播放趋势
音乐人任务
账号云豆数
领取云豆
获取 VIP 信息
音乐人签到
获取客户端歌曲下载 url
获取歌单所有歌曲
乐签信息
获取歌手视频
最近播放-歌曲
最近播放-视频
最近播放-声音
最近播放-歌单
最近播放-专辑
最近播放-播客
签到进度
重复昵称检测
歌手粉丝数量
音乐人任务(新)
内部版本接口
歌单更新播放量
黑胶时光机
音乐百科 - 简要信息
乐谱列表
乐谱内容
曲风列表
曲风偏好
曲风详情
曲风-歌曲
曲风-专辑
曲风-歌单
曲风-歌手
{% endfolding %}

api调用地址:https://xyz.jywl.fun/


emm…肝不动了。。。先写到这吧。嘿嘿