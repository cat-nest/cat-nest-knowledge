# 整体设计

## 用户中心设置

+ 个人信息设置（昵称）
+ 符合网络规范的个人信息设置
+ 账户信息（密码等）
+ 实行积分制，将用户可以进行操作的部分，进行积分限定【区分用户，一个相对独立的产品，可以对用户进行一定筛选，由于是交互式较强的系统，避免劣质用户影响体验】



## 用户空间

+ 最上层类似项目，项目下面是文件夹，该部分设计较为模糊，

  项目以及文件夹可以上锁，但是上锁文件夹以及其子文件夹都是全部上锁状态【就是要么全锁，要么全不锁】

  该功能的设计要点是，主要是摆脱单一的文件【猫窝】—与单体用户关系，

  该种关系让用户，在单个文件活跃后，难以让他人留意自己更多，所以推出用户空间功能，类似，从单一文件到文件集，系列这种从单一活跃到带动多个活跃状态



## 功能设置

+ UI开关【猫窝UI展示/极简显示】
+ 缩略图展示开关、预览自动播放
+ 这部分我个人经验不多，也可以说是产品使用经验较少，暂时想到，后续补充





## 文件模块

+ 文件上传
+ + 文件本体
  + 公开开关
  + 文字简介
  + 简介图
  + + 默认方式
    + + 图片：压缩图片
      + 文本文件：根据题目自动生成简介图
      + 视频：第一帧作为首页
      + 压缩包：官方UI/同文本文件+颜色底纹
    + 自定义
    + + 用户上传图片
  + 悬浮播放（限定文件格式？）
  + + 默认方式
    + + 视频跳帧播放
    + 自定义
    + + 用户上传gif、短视频
+ 文件默认附带猫窝
+ + 文字简洁
  + 猫窝单独上锁
+ 关于猫窝的聊天范畴功能，后续细化考虑
+ 文件-猫窝——卡片化定格，类似小名片
+ 分享功能【设置期限】
+ 文件修改
+ + 非活跃文件修改【快速】
  + 活跃文件的修改【需要进行审核，以免积极内容修改成消极内容传播】



+ 公开文件、猫窝的查看【各种排行榜】





## 系统功能

+ 文件上传后建议审核
+ 活跃文件安全审核机制
+ 增删改查
+ 可怕强大，热点推送及【用户个性化/默认】