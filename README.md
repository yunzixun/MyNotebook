# MyNoteBook 万事本 
### 一款简单易用的记事本
数据库FMDB的简单实用，涉及数据库的增删改查

![gif](https://github.com/RiberWang/MyNoteBook/blob/master/Screenshot/MyNotebook.gif)

### 更新日志  
1.应用加图标,修改 return 键不再保存,而是换行  
2.解决 seachBar 搜索时,点击 seachBar 键盘一会隐藏一会退出 bug  
3.添加按钮为灰色,如果 cell 里面有内容,此时处于编译状态,点击 edit 退出编辑后,添加按钮还是不可用,已修复  

2015.10.27  
字体样式统一

2015.10.28  
添加多个 targets

2015.11.3  
仿 iOS 短信页面处理  
1.编辑按钮 实现编辑 和保存,编辑时 添加按钮置灰  
2.搜索时 导航条上移,取消时下移 并添加动画效果  
 
2015.11.4  
1.在滚动到下面时 搜索 自动返回上面位置  
2.处于搜索时 点击collectionView 退出搜索 如果是点在详情页面上 使其不进入详情页面  
3.处于搜索时,输入框无文本时 退出搜索状态 有文本时不退出  
4.修正2 ,3处于搜索时,搜索框无文本 点击退出搜索 有文本 点击 进入详情页面  
*3.zip  
  
2015.11.5  
1.在搜索时 处于后台 导航会自动回到原位置 后台处理调用 searchBar 的 cancel 按钮事件  
2.搜索时 进入详情页面 数据不对  
3.剔除 cell 长按手势    
4.搜索时 解决 从详情页面返回时 导航栏从下往上隐藏的动画 
5.解决 测试版警告问题  
*4.zip 最新版  
  
2015.11.9  
1.添加appIcon  
2.处理搜索时 使用拼音搜索 没按确认键时 数组为空 点击 cell 崩溃  
3.新增的页面图片的右上角显示不完全  
*5.zip  
  
2015.11.18  
1.搜索时进入详情页 有问题  
2.第一次进入首界面 进不去详情页  
3.ios6崩溃  
4.简单适配 ios6  
5.修复搜索后 点击取消 数组没清空的 bug  
*5.zip  
  
2015.11.20  
1.适配支持 ipad 不让其横屏  
  
2015.11.27  
最终版appIcon  
*5.zip  
  
2016.1.17  
编辑时出现的删除按钮 适配  
*6.zip  
  
2016.1.28  
1.app只支持7.0以上 舍弃6.0  
2.解决ios7 处于搜索时 进入详情页 导航消失  
3.视图view背景变灰色 与collectionView颜色相同  
4.解决未知bug:处于搜索时 进入详情 进行后台操作 返回时 导航栏不下来  
5.添加本地通知(待完善)  
*7.zip  
  
2016.1.29  
1.textView适配 详情和添加位置不同 大小不同  
2.handoff添加(未完成)  

2016.1.31  
1.handoff 程序启动 添加 完成 蓝牙连接  
2.本地通知 设置每天  
*8.zip  
  
2016.2.19  
1.适配iPad 在universal情况下  
2.添加适用设备为iphone iPad上显示iphone4的尺寸  
3.本地通知设置 2天后不打开app 则发送一个通知  
*8zip  
  
2016.3.6  
1.添加摇一摇功能  
2.在键盘上新增一个完成按钮  
*8zip  
  
2016.5.10  
1.添加分享功能 进行中…  
  
2016.6.23  
1.日期适配屏幕  
*9zip  
  
2016.7.14  
1.textView添加 无文本时提示框  
2.分享添加成功  
*10.zip  
  
2016.7.26  
1.正式版 分享头文件添加  
2.搜索的cancel改为文字取消  
3.详情页 修改文本时 添加撤销功能  
4.分享添加成功  
5.更新时间  
  
2016.7.29  
1.进入添加页时 点击键盘的提示文字 placehoder不会消失  未输入文本时 不让键盘的提示文字显示
    _textView.autocorrectionType = UITextAutocorrectionTypeNo;  
2.撤销功能bug修复 文本  
*10.zip  
  
2016.8.10  
1.添加作者信息页面 appstore好评  
2.添加作者信息页面 设置通知  
*11.zip  
  
2016.11.2  
1.添加Today 并配置证书  
2.添加本地中文化  
*12.zip  
  
2016.11.20  
1.适配qq电话打电话 等视图下移问题  
2.添加手势侧滑返回  
*12.zip  
  
  
  
已知 bug:  
1.第一次删除的时候闪退 已解决  
2.搜索时删除 有问题  已解决  
3.第一次安装会崩溃 已解决  
4.键盘适配  已解决  
5.ios7 搜索时进入详情 导航 消失不见了  已解决  
6.修改内容时时间不能更新 已解决  
7.适配打电话 已解决  
8.处于搜索时 进入详情 返回首页面 点击取消 导航栏编程透明了 （设置导航栏不透明 视图位置全部下移 状态栏无法改变）

### [AppStore下载地址](https://itunes.apple.com/cn/app/万事本/id1057007765?mt=8!)
