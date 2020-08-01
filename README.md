一、	项目概述
      本次项目设计为贪吃蛇，实现了蛇身的增长、键控、苹果的随机出现和通过HDMI以1080p分辨率输出。因为按键不足所以设计时，取消了按键控制，让蛇自动去吃苹果，不够也涉及了键控模块，可以很方便的组装。
      
二、	使用工具
      Vivado 2018.3
      
三、	小组成员
      组长	刘进圆	20AS105A
      组员	陈红利	20AS107A
      组员	邓晓琴	20AO199A
      
四、	板卡型号与外设
      板卡型号：sea-s7    外设：1080p显示屏
      
五、	仓库目录介绍
      images：存放照片。
      Sourcecode：存放源码。
      ExecutableFiles：存放bit文件。
      
六、	代码说明
      在sourcecode文件夹内：
      Snake：为蛇身控制模块。
      Apple：为苹果随机出现模块。
      VGA：为视频输出模块。
      Top：为顶层模块。
      Block：为块大小控制模块。
      Key：为键控模块。
