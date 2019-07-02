## [2014.2.3] 2015-05-04


## [2014.2.1] 2015-02-11


## [2014.2] 2014-12-31


## [4.10.12] 2019-06-25

*  删除内网不允许更新的限制
*  修复导航条会抢占一次焦点

## [4.10.11] 2019-06-14

*  适配用户密码被删除的情况
*  修复用户详情界面布局错乱
*  修复快捷键显示有重叠
*  修复用户修改密码时错误提示不会消失
*  修复多屏幕在合并模式下修改分辨率会退出合并模式

## [4.10.10] 2019-06-13

*  更新专业版用户许可协议

## [4.10.9] 2019-06-11

*  处理用户没有密码的情况
*  支持配置文件优先级

## [4.10.8] 2019-06-04

*  添加云同步模块
*  修复settingsiem换行问题

## [4.10.7] 2019-06-01

*  修复没有刷新指纹设备
*  修改鼠标移动的最低值

## [4.10.6] 2019-05-29

*  修复新建用户的密码错误提示不会消失
*  补充sw平台丢失的mieee编译参数

## [4.10.5] 2019-05-23

*  快捷键添加一键恢复按钮
*  丢失polkit policy文件
*  修复自定义模式下合并屏幕后调节分辨率会拆分屏幕

## [4.10.4] 2019-05-13

*  音效列表没有翻译

## [4.10.3] 2019-05-10


## [4.10.2] 2019-04-25


## [4.10.1] 2019-04-25

*  修复音效界面没有标题

## [4.10.0] 2019-04-19

*  修复网络ipv4的子网掩码的有效性检查 https://github.com/linuxdeepin/internal-discussion/issues/1427
*  修复2d下屏幕旋转没有适配高分屏 https://github.com/linuxdeepin/internal-discussion/issues/1458
*  修复无线网络链接列表的动画没有居中 https://github.com/linuxdeepin/internal-discussion/issues/1411

## [4.9.13] 2019-04-15

*  优化无线列表的排序
*  修复多屏缩放相关问题
*  修复音效界面没有标题
*  修复无限投屏相关问题

## [4.9.12] 2019-04-10

*  翻译
*  修复无法使用 ESC 键退出屏幕旋转界面

## [4.9.11] 2019-04-10


## [4.9.10] 2019-04-09

*  修复窗口大小错误
*  修复通知的音效示例效果和实际播放的效果不同 https://github.com/linuxdeepin/internal-discussion/issues/1160
*  修复显示模块在多屏环境下相关设置没有显示
*  新增音效开关的显示区分台式机和笔记本

## [4.9.9.4] 2019-04-08


## [4.9.9.3] 2019-04-01

*  修复多屏下控制中心大小不正确
*  修复arm下没有禁用电源模块
*  修复音效界面声音预览不一致

## [4.9.9.2] 2019-03-28


## [4.9.9.1] 2019-03-27

*  新增对显示模块进行旋转等设置后超时还原的功能，避免黑屏后无法操作 https://github.com/linuxdeepin/internal-discussion/issues/982
*  修复右边屏幕对齐不正确 https://github.com/linuxdeepin/internal-discussion/issues/1003
*  移除显示模块配置列表功能 https://github.com/linuxdeepin/internal-discussion/issues/992
*  检查更新提示错误 https://github.com/linuxdeepin/internal-discussion/issues/1035
*  修复网络模块选择秘钥文件时点击对话框后控制中心会隐藏 https://github.com/linuxdeepin/internal-discussion/issues/1028
*  修复从其他位置激活一个无线网时控制中心的列表中不会显示正在激活哪一个 https://github.com/linuxdeepin/internal-discussion/issues/525
*  修复默认应用模块部分文案没有翻译 https://github.com/linuxdeepin/internal-discussion/issues/1092
*  修复网络模块 ipv6 方法无法从手动直接切换到忽略 https://github.com/linuxdeepin/internal-discussion/issues/1121
*  修复搜索框中文案翻译问题
*  修复无线网名称长度超过32位后无法保存且没有提示

## [4.9.9] 2019-03-26


## [4.9.8] 2019-03-19


## [4.9.7] 2019-03-13


## [4.9.6] 2019-03-06

*  update

## [4.9.5] 2019-03-05


## [4.9.4] 2019-02-25

*  添加依赖关系错误检查 https://github.com/linuxdeepin/internal-discussion/issues/815
*  修复通知的日期错误
*  修复刷新默认程序列表时，错误的清空列表
*  修改启用窗口特效的文案 https://github.com/linuxdeepin/internal-discussion/issues/900
*  修复显示模块在只显示单屏时没有记录主屏

## [4.9.3] 2019-02-25


## [4.9.2.1] 2019-01-28

*  新增 SSTP VPN 代理支持
*  修复账户界面显示问题
*  修复热点加密模式无法设置为 wep

## [4.9.2] 2019-01-25

*  特效开关状态错误
*  新建用户时，删除开头的字符，光标会回到结尾
*  添加音效设置页面
*  sw启用网络代理、旋转、声音反馈和时区设置
*  支持sstp vpn  https://github.com/linuxdeepin/internal-discussion/issues/560
*  修复创建openvpn时，tls不可见 https://tower.im/teams/9487/todos/228437/
*  修复通知时间被截断 https://tower.im/teams/9487/todos/228389/
*  删除不需要处理的update job https://github.com/linuxdeepin/internal-discussion/issues/876

## [4.9.1] 2019-01-15

*  修复快捷键没有换行显示 https://github.com/linuxdeepin/internal-discussion/issues/724
*  修复密码强度检查的提示没有翻译
*  更新翻译 https://github.com/linuxdeepin/internal-discussion/issues/683

## [4.9.0] 2019-01-10

*  修复通知没有对过长文字进行裁剪 https://github.com/linuxdeepin/internal-discussion/issues/769
*  修复更新提醒没有换行
*  获取声音信息失败 https://github.com/linuxdeepin/internal-discussion/issues/805
*  修复替换快捷键失败 https://github.com/linuxdeepin/internal-discussion/issues/812
*  删除用户时取消对话框，导致用户被删除 https://github.com/linuxdeepin/internal-discussion/issues/752

## [4.8.7.2] 2019-01-04

*  修改导入导出 VPN 时默认为 HOME 目录 https://tower.im/teams/9487/todos/224249/
*  修复没有显示当前键盘布局和语言 https://tower.im/teams/9487/todos/226068/
*  修复掌压调整的 slider 行为与其他类似控件不同 https://tower.im/teams/9487/todos/226218/
*  修复连接 VPN 后有线网络不显示当前已激活的连接 https://github.com/linuxdeepin/internal-discussion/issues/664
*  修复单屏幕与多屏幕切换的问题
*  修改默认禁用密码强度检查

## [4.8.7.1] 2018-12-28

*  修复键盘模块导致崩溃
*  默认禁用密码强度检查

## [4.8.7] 2018-12-24

*  更新用户协议
*  支持用户密码强度检查
*  修复默认程序列表没有刷新
*  修复自动下载关闭后没有隐藏提示
*  修复时间设置页面的时间不正确
*  修复快捷键内容空白
*  修复语言列表空白
*  修复更新存在空指针异常
*  修复搜索语言后没有标识当前的语言

## [4.8.6] 2018-12-19

*  修复编译失败

## [4.8.5] 2018-12-19


## [4.8.4] 2018-12-18

*  修复智能镜像源没有刷新

## [4.8.3] 2018-12-17

*  添加智能镜像源

## [4.8.2] 2018-12-13

*  更新最终用户协议
*  修复版本号没有从/etc/deepin-version读取

## [4.8.1] 2018-12-12

*  修复语言列表不能触屏滚动
*  修复禁用更新提醒时没有隐藏自动下载更新的提示 https://github.com/linuxdeepin/internal-discussion/issues/584
*  修复关闭更新提醒时没有禁用自动下载更新 https://github.com/linuxdeepin/internal-discussion/issues/585
*  优化通知的滚动卡顿

## [4.8.0] 2018-12-07

*  ipv6不能设置为忽略 https://tower.im/projects/e4ae1ad0b5d5497fb4b7c14fe2d2efbf/todos/88ebe71134041d09da0b1c4a5d8844e3/
*  错误保存vpn的组密码 https://github.com/linuxdeepin/internal-discussion/issues/529
*  关闭蓝牙设备重新进入，会显示已连接的列表
*  缩放滑动条的初始值错误
*  限制grub拖放图片的类型 https://github.com/linuxdeepin/internal-discussion/issues/553
*  更新模块changelog显示有截断 https://github.com/linuxdeepin/internal-discussion/issues/418
*  更新详情有两个系统补丁
*  切换到自动之后，手动配置的网关没有被清空  https://tower.im/projects/e4ae1ad0b5d5497fb4b7c14fe2d2efbf/todos/9da5774fb281695e4fa46625db88da59/
*  ipv6前缀初始化错误 https://tower.im/projects/e4ae1ad0b5d5497fb4b7c14fe2d2efbf/todos/7891a09c1b34dd53f67534abd1933611/
*  添加更新提醒按钮 https://github.com/linuxdeepin/internal-discussion/issues/519
*  网络连接编辑 内部认证默认为空 https://github.com/linuxdeepin/internal-discussion/issues/515

## [4.7.9] 2018-12-04

*  修复设置缩放失败
*  修复台式机可以显示电池配置 https://github.com/linuxdeepin/internal-discussion/issues/542

## [4.7.8] 2018-11-30

*  [1] https://github.com/linuxdeepin/internal-discussion/issues/499
*  支持调整缩放系数到3x [1]
*  修复控制中心自动下载后提示没有更新为已下载
*  去掉不透明度的数值 [2]
*  分离电源设置为直流电和使用电池 [3]
*  更新grub界面的提示 [4]
*  系统补丁有两个 [5]

## [4.7.7] 2018-11-23

*  去除个性化中透明度数值的显示
*  禁用grub列表的右键菜单
*  允许grub列表拖拽新的图片

## [4.7.6.2] 2018-11-22

*  rebuild

## [4.7.6.1] 2018-11-19


## [4.7.6] 2018-11-13

*  修复双屏列表保存失败
*  修复快捷键没有简写control

## [4.7.5] 2018-11-13

*  修复默认程序列表会随机不显示数据

## [4.7.4] 2018-11-09

*  保存网络配置以后自动连接
*  修复不能创建热点
*  修复导航栏闪烁
*  修复隐藏控制中心后导航提示没有隐藏
*  修复个性化偶然出现没有设置默认值
*  添加pppoe连接效果

## [4.7.3] 2018-11-02

*  修复无法连接空密码wifi和隐藏wifi
*  修复不能保存pppoe的编辑
*  修复没有蓝牙设备但首页显示蓝牙图标

## [4.7.2] 2018-11-01

*  修复编译错误
*  更新grub 主题的描述
*  修复浮点数计算错误
*  修复添加快捷键时没有标题
*  编辑有线网的mac地址
*  修复通知不能取消最后一项的hover

## [4.7.1] 2018-10-26

*  修复编辑快捷键时崩溃

## [4.7.0] 2018-10-25


## [4.6.4.11] 2018-10-26


## [4.6.4.10] 2018-10-24


## [4.6.4.9] 2018-10-12


## [4.6.4.8] 2018-09-27


## [4.6.4.7] 2018-09-19


## [4.6.4.6] 2018-09-13


## [4.6.4.5] 2018-09-13


## [4.6.4.4] 2018-09-07


## [4.6.4.3] 2018-09-07


## [4.6.4.2] 2018-09-07


## [4.6.4.1] 2018-08-31


## [4.6.4] 2018-08-12


## [4.6.3] 2018-08-07


## [4.6.2] 2018-07-31


## [4.6.1] 2018-07-20


## [4.6.0] 2018-07-20


## [4.5.5] 2018-06-12


## [4.5.4] 2018-06-07


## [4.5.3] 2018-05-31


## [4.5.2] 2018-05-30


## [4.5.1] 2018-05-29


## [4.5.0] 2018-05-24


## [4.4.4.4] 2018-06-27


## [4.4.4.3] 2018-05-23


## [4.4.4.2] 2018-05-14


## [4.4.4.1] 2018-04-11


## [4.4.4] 2018-03-28


## [4.4.3] 2018-03-26


## [4.4.2] 2018-03-22


## [4.4.1] 2018-03-16


## [4.4.0] 2018-03-08


## [4.3.7] 2017-11-29


## [4.3.6] 2017-11-28


## [4.3.5] 2017-11-24


## [4.3.4] 2017-11-23


## [4.3.3] 2017-11-16


## [4.3.2] 2017-11-09


## [4.3.1] 2017-11-03


## [4.3.0] 2017-10-27


## [4.2.5.13] 2017-10-26


## [4.2.5.12] 2017-10-26


## [4.2.5.11] 2017-10-25


## [4.2.5.10] 2017-09-21


## [4.2.5.9] 2017-09-21


## [4.2.5.8] 2017-09-14


## [4.2.5.7] 2017-09-14


## [4.2.5.6] 2017-08-25


## [4.2.5.5] 2017-08-24


## [4.2.5.4] 2017-08-18


## [4.2.5.3] 2017-08-18


## [4.2.5.2] 2017-08-18


## [4.2.5.1] 2017-08-17


## [4.2.5] 2017-07-21


## [4.2.4] 2017-07-20


## [4.2.3] 2017-07-14


## [4.2.2] 2017-07-13


## [4.2.1] 2017-07-06


## [4.2.0] 2017-06-27


## [4.1.2] 2017-04-17


## [4.1.1] 2017-04-14


## [4.1.0] 2017-04-13


## [4.0.16] 2017-04-06


## [4.0.15] 2017-04-05


## [4.0.14] 2017-03-22


## [4.0.13] 2017-03-22


## [4.0.12] 2017-03-22


## [4.0.11] 2017-03-22


## [4.0.10] 2017-03-16


## [4.0.9] 2017-03-15


## [4.0.8] 2017-03-10


## [4.0.7] 2017-02-24


## [4.0.6] 2017-02-23


## [4.0.5] 2017-02-22


## [4.0.4] 2017-02-21


## [4.0.3] 2017-02-20


## [4.0.2] 2017-01-18


## [4.0.1] 2017-01-17


## [4.0.0] 2017-01-13


## [3.0.24] 2016-11-29


## [3.0.23] 2016-10-31


## [3.0.22] 2016-10-17


## [3.0.21] 2016-09-28


## [3.0.20] 2016-09-13


## [3.0.19] 2016-09-05


## [3.0.18] 2016-09-01


## [3.0.17] 2016-09-01


## [3.0.16] 2016-08-23


## [3.0.15] 2016-08-19


## [3.0.14] 2016-08-12


## [3.0.13] 2016-05-26


## [3.0.12] 2016-05-20


## [3.0.11] 2016-05-12


## [3.0.10] 2016-03-07


## [3.0.9] 2016-02-23


## [3.0.8] 2016-02-18


## [3.0.7] 2016-01-27


## [3.0.6] 2016-01-22


## [3.0.5] 2016-01-14


## [3.0.4] 2016-01-12


## [3.0.3] 2016-01-06


## [3.0.2] 2015-12-30


## [3.0.1] 2015-12-29


## [3.0.0] 2015-12-28


## [2.91.6] 2015-12-21


## [2.91.5] 2015-12-18


## [2.91.4] 2015-12-10


## [2.91.3] 2015-12-09


## [2.91.2] 2015-11-20


## [2.91.1] 2015-11-19


## [2.91.0] 2015-11-03


## [2.90.3] 2015-08-31


## [2.90.2] 2015-08-20


## [2.90.1] 2015-06-26


## [2.90.0] 2015-06-17


## [2.4.1] 2015-10-08


## [2.3.2] 2015-10-08


## [2.3.1] 2015-06-17

