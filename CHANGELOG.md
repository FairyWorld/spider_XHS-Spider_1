# 更新日志

## `2023/11/19 v1.0.2.8

- 新增功能
  - 搜索栏支持短链接笔记搜索
  - 批量导入支持短链接地址批量导入与解析
  - 导出Excel时，增加点赞数量、收藏数量、评论数量、分享数量、笔记发布时间等数据
- 优化功能
  - 优化导出Excel时，笔记标签取值逻辑
  - 优化其他已知问题

## `2023/11/15 v1.0.2.7

- 新增功能
  - 解析时增加笔记发布时间，支持点击列头排序
- 优化功能
  - 修复系统设置不创建子文件夹时，由于文件命名规则重复，导致文件被覆盖问题
  - 修复解析笔记时异常退出问题

## `2023/11/13 v1.0.2.6

- 新增功能
  - 小程序上线，授权过期后，可通过界面提示授权过期，扫小程序二维码，每天可申请延期3次，一次30分钟
- 优化功能
  - 修复点击收藏夹时，由于部分采集数据异常，导致程序闪退问题
  - 修复其他已知bug

## `2023/11/09 v1.0.2.5

- 优化功能
  - 紧急修复2.4版本增加封面问题带来的爬取、解析部分博主时程序崩溃问题

## `2024/11/05 v1.0.2.4

- 新增功能
  - 增加导出评论功能
  - 增加下载视频封面设置、同时增加下载时根据下载封面设置，自动判断封面是否需要下载
- 优化功能
  - 修复博主页面导出excel时，封面数据取值错误问题
  - 文件下载命名调整为[标题]-[序号]

## `2023/10/28 v1.0.2.3

- 特别说明
  - 本次新增功能较多，[请自行查看文档系统功能](https://xisuo67.website/XHS-Spider-Doc/backend/system/home.html)
- 新增功能
  - 系统设置新增【解析速度】，允许用户自行设置解析速度，未设置时默认2秒（时间越短，越容易触发反扒，并且封号）
  - 系统设置新增【自动下载】，开启该功能后，将在解析完后，立即自动下载（如果部分数据需要手动下载，请勿开启该参数）
  - 新增批量导入模板，允许用户批量导入【单条】笔记链接进行解析，解析完成后可导出解析数据，具体操作步骤[请自行查看文档系统功能](https://xisuo67.website/XHS-Spider-Doc/backend/system/home.html)
  - 博主合集页面，增加导出Excel功能
  - 博主合集页面，增加笔记or视频筛选功能
- 优化功能
  - 优化博主合集页面布局
  - 修复下载后程序未关闭情况下，二次下载无反应，以及下载不提示问题
  - 修复下载完成后，未弹窗提醒且未释放内存问题

## `2023/10/23 v1.0.2.2

- 优化功能
  - 紧急修复Issues下载的图片都是“lisa银发灰色” #121

## `2023/10/21 v1.0.2.1

- 特别说明
  - 由于近期发现很多淘宝、咸鱼店主将本软件作为付费资源售卖，并且把作者作为售后，引导用户加群找作者解决问题，考虑以上种种原因紧急发布2.1版本，程序启动时增加弹窗提醒。
  - 同时，作者不是售后，自行学习软件使用方法
- 新增功能
  - 启动软件时增加弹窗提醒
  - 博主页面增加【关注】功能，点击【关注】，即可将博主首页添加至关注列表中，方便下次快速访问
  - 新增【关注】菜单栏，可根据已关注列表中数据，快速访问博主首页

## `2023/10/15 v1.0.2.0

- 新增功能
  - 2.0增加系统设置，是否监听剪切板事件，避免最小化托盘时，因为误操作导致解析文件失效
  - 2.0版本增加是否创建子文件夹选项
    - 是：则保持现状，文件夹创建规则：博主名称/标题/文件
    - 否：文件夹创建规则：博主名称/文件
  - 增加采集数据过滤功能，已采集数据允许过滤，只查看最新博主发布笔记
- 优化功能
  - 恢复原图下载
  - 优化授权功能
  - 优化搜索页面，允许单条笔记，博主主页来回切换，不再当前URL不符合所属模块搜索要求。

## `2023/09/11 v1.0.1.9

- 优化功能
  - 由于小红书接口调整，紧急修复图片下载失败Bug
  - 修复单条笔记下载图片失败问题

## `2023/09/09 v1.0.1.8

- 本次更新内容较多，[详细内容查看官网](https://xisuo67.website/XHS-Spider-Doc/backend/setting.html)
- 新增功能
  - 增加程序自动更新功能
  - 增加下载完成提示设置
  - 增加下载查询功能，用于主动查询当前后台下载任务剩余数量
- 优化功能
  - 修复更新配置参数时，没有立即生效问题
  - 修复其他已知bug

## `2023/08/27 v1.0.1.7

- 优化功能
  - 采集大量数据时，内存异常飙升，导致程序无响应/闪退的问题修复

## `2023/08/16 v1.0.1.6

- 新增功能
  - 新增设置是否登录功能（系统设置开启自动登录，且扫码登录成功后，下次重启软件将自动登录）
- 优化功能
  - 紧急优化v1.0.1.5版本偶发调用扫码登录接口失败以及采集笔记时提示cookie为空问题

## `2023/08/14 v1.0.1.5

- 更新功能
  - 新增功能
    - 新增程序启动读取授权文件功能（v1.0.1.5版本后，所有版本将使用授权文件才能启动程序）
    - 增加设置主题、文件下载地址、是否下载文案等系统设置功能，程序重启后依然生效
    - 新增托盘功能，最小化到托盘，显示、隐藏等
  - 优化功能
    - 修复全选只能全选当前页，无法全选所有问题
    - 优化部分接口调用成功却无数据返回，导致程序报错问题
    - 优化程序背景图片根据主题颜色自动切换
    - 优化程序图标
    - 优化托盘多个空格问题

## `2023/07/08 v1.0.1.4

- 更新功能
  - 修复切换tab页签时，全选无法选中问题
  - 修复扫码登录空对象问题
  - 修复其他已知问题

## `2023/06/20 v1.0.1.3

- 更新功能
  - 移除所有不该存在的

## `2023/06/1`5 v1.0.1.2

- 更新功能
  - 新增功能
    - 点击头像跳转个人主页
    - 增加收藏、点赞页签
    - 设置界面新增捐赠、联系作者
  - 优化功能
    - 登陆后头像获取失败问题
    - 扫码登录弹窗增加提示小红书app扫码登录
    - 其他已知bug修复

## `2023/06/08` v1.0.1.1

- 更新功能
  - 新增功能
    - 增加文案采集
  - 优化功能
    - 文件夹命名规则调整，由原来笔记名称，调整为【笔记发布日期_笔记名称】

## `2023/06/05` v1.0.1.0

- 更新功能
  - 新增功能
    - 单条笔记采集
  - 优化功能
    - 修复扫码登录时，获取全局当前登录用户部分数据为空时，获取用户头像失败，导致程序异常退出bug

## `2023/06/04` v1.0.0.9

- 更新功能
  - 新增功能
    - 新增扫码登录（暂时不支持微信扫码登录）
  - 优化功能
    - 删除添加cookie入口，以扫码登录取代
    - 删除cookie管理入口，以扫码登录取代
    - 部分代码重构，优化已知bug
  - 功能预览
    - [bilibili](https://www.bilibili.com/video/BV1UW4y1R7GE/?spm_id_from=333.999.0.0) 

## `2023/05/23` v1.0.0.8

- 更新功能
  - 新增功能
    - 增加笔记解析，未解析笔记不允许直接下载
  - 优化功能
    - 增加笔记总数
    - 动态显示笔记解析进度
    - 调整笔记采集接口请求速度，大幅降低接口调用频率，防止暴力采集导致ip禁用，保护小红书服务器避免过度采集
  - 升级
    - 运行时升级为.Net 6.0
- 功能预览
  - [bilibili](https://www.bilibili.com/video/BV1Wc411A7Fy/?vd_source=e2562a684d381def8f9af230a7396690)


## `2023/05/20` v1.0.0.7

- 更新功能
  - 允许网页版小红书登录后，从浏览器中获取cookie，并手动在程序中设置cookie

## `2023/05/19` v1.0.0.6

- 更新功能
  - 更新x-s获取方式
  - 自动获取cookie
  - 移除设置cookie入口
  - 暂时不支持登录后的cookie设置
  - 待下个版本回复手动设置cookie

## `2023/05/14` v1.0.0.5

- 更新功能
  - 小优化，修复小红书博主笔记标题不合规创建文件夹失败，导致异常退出问题

## `2023/05/12` v1.0.0.4

- 更新功能
  - 修复bug，cookie使用多次后，小红书接口不存在更多时依然会返回存在多条标识，导致界面显示辣鸡数据
  - 修复异常退出
  - 新增监听剪切板功能，满足系统要求链接，在搜索界面，可以快速跳转至相应页面并刷新界面数据

## `2023/05/10` v1.0.0.3

- 更新功能
  - 用户笔记添加勾选框，允许勾选多个笔记批量下载
  - 用户笔记增加搜索框，根据关键字快速搜索相关笔记
  - 修复博主首页无性别时，程序异常的bug

## `2023/05/09` v1.0.0.2

- 更新功能
  - 修复如果多条笔记标题一样，导致文件下载有误的bug。文件名称调整为笔记标题+guid

## `2023/05/08` v1.0.0.1

- 更新功能
  - 修复已知bug，自动更新检测未能成功检测
  - 调整联系方式，联系方式改为群聊，点击首页QQ群，唤起网页跳转QQ群功能（需要登录QQ）
- 下版本迭代计划：
  - 自动获取cooike
  - 新增数据存储
    - 存储用户设置信息

## `2023/05/05` v1.0.0.0

* 新增功能：

  * 自动检测软件更新
  * 添加cookie
  * 搜索
  * 批量下载小红书博主首页下所有笔记
  * 下载完成通知

* 下版本迭代计划：

  * 新增数据存储

    * 存储用户设置信息

  * 小红书首页功能接入

    * 首页卡片页面

    * 勾选首页卡片，下载笔记

    * 通过首页展示数据，快速导航小红书博主页面

      

    

  
