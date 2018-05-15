源码分析
--------
* libdispatch： GCD（Grand Central Dispatch，多核并行运算解决方案）源码
* iOS Runtime： iOS运行时系统 
* Alamofire:  iOS系统上Swift语言的网络请求库
* SDWebImage： iOS系统上OC语言的图片缓存库
* Realm： Realm数据库

控件篇
--------
* UIViewController
	* [UIViewControllerAnimatedTransitioning](https://blog.csdn.net/qq_27736043/article/details/50312717) 转场中应该做些什么
	* [UIPercentDrivenInteractiveTransition Controller交互式转场切换动画](https://blog.csdn.net/chengkaizone/article/details/48621161)
	* Child View Controller
		* [willMoveToParentViewController和didMoveToParentViewController
](https://blog.csdn.net/yongyinmg/article/details/40619727)
* Auto Layout
	* [官方文档](https://developer.apple.com/library/content/documentation/UserExperience/Conceptual/AutolayoutPG/AnatomyofaConstraint.html#//apple_ref/doc/uid/TP40010853-CH9-SW1)
* 手势 UIGestureRecognizer
	* [手势的3个容易混淆的属性 cancelsTouchesInView/delaysTouchesBegan/delaysTouchesEnded](https://blog.csdn.net/fys_0801/article/details/50605837)
* UIFont
	* iOS支持的字体
		* [http://iosfontlist.com](http://iosfontlist.com/)
		* [http://www.iosfonts.com/](http://www.iosfonts.com/)

模块篇
--------
* Core Image
* Core Animation

开发流程
--------
* [使用 Quick、Nimble 执行测试驱动开发（TDD）](http://www.cocoachina.com/ios/20171114/21160.html
FBSnapshotTestCase Nimble)

常用的Framework
--------
* Snapkit Swift手写UI库，AutoLayout
* RxSwift Reactive响应式编程的Swift实现
* RxCocoa RxSwift的Cocoa框架的扩展
* PopupDialog 可自定义的PopupViewController实现

学习研究用的Framework
--------
* [一行代码让TableView动起来](https://github.com/alanwangmodify/TableViewAnimationKit)
* 

Swift
--------

## **Tips**

* 1. init时的处理
	* 先初始化子类成员，再调用Super的初始化
* 2. 编码规范
	* [Swift Lint](https://github.com/realm/SwiftLint) 强制使用者按照规范编码
	* 私有变量禁止使用 _ 开头
* 3. [自动计算TableViewCell高度](https://blog.csdn.net/u011043997/article/details/51263016)
* 4. Swift 允许在Framework中使用静态库
	* (Allow Non-modular Includes In Framework Modules) 允许静态库，不优雅，没办法

	
算法学习
--------
* 排序算法
* 红黑树
* 平衡二叉树

工作计划
--------
* Weather Application
* Game: Fight Forever
* Framework: HeWeather Api (iOS)