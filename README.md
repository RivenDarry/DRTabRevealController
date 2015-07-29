# DRTabRevealController
一个封装好的侧滑菜单栏, 通过简单的初始化就可以使用

两步初始化操作:
1. 开辟空间并初始化界面数组
  DRTabRevealController *tabreveal = [[DRTabRevealController alloc]initWithReavealControllers:@[firNav, secNav]];
2. 设定菜单界面
  tabreveal.tabController = menuVC;
  
更多个性化操作:
 tabreveal.choosenIndex 可以定义初始界面
 tabreveal.menuBt 导航栏小图标接口, 可个性化定制
