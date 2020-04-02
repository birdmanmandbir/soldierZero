# Soldier Zero
*Computer Graphics Game Project*

![](screenShots/startScene.png)

作为一名使用超能力的士兵，你的任务是拿到钥匙卡，寻找目标地点（目标地点地上漂浮着绿色圆圈）

游戏中有3种不同的敌人, 体型越大血量越高, 但伤害越低, 所以一定要小心小个子敌人!

如果你发现游戏过难, 可以按Q使用子弹时间技能, 敌人和你的速度都会变慢!

Tips：有两条各有特色的路线可以到达终点，选择你最喜欢的一条， enjoy it！

![](screenShots/battle1.png)

![](screenShots/battle2.png)

## TODO List

- [x] UI
  - [x] 开始画面
  - [x] 按键配置
- [x] ESC or 菜单页面退出游戏
  - [ ] 子弹时间时画面变暗, 敌人高亮, 可否做到?
- [ ] 传送门
  - [ ] 玩家创建传送门(黄)
  - [x] 方向bug(黄)
- [ ] 子弹实体
  - [ ] 更换模型
- [x] 关卡设计(范)
- [x] 敌人配置(范)
- [x] Bug
  - [x] AI穿模
  - [x] 抬头时场景穿模
- [ ] 配音
  - [ ] 技能声音
  - [ ] 背景音乐
- [x] 开场动画(黄)


##  AI（范）
1. 更智能的AI，更多的机制。
    1. 如果技能点点在潜行, 就缩小视角, 但是减少主角血量
    
##  武器建模（范）
可以多设计几种武器模式
不同的炮弹颜色表示传送门和攻击
    
## 链接
[Git团队协作使用规范](https://blog.csdn.net/u011077672/article/details/78819324)  
[Unity3d第一人称射击游戏项目实战](https://www.bilibili.com/video/av37116509?from=search&seid=13139258492896819105)  
[微元素(素材网)](https://www.element3ds.com/)  
[github上fork原项目，如何将本地仓库代码更新到最新版本？](https://www.cnblogs.com/eyunhua/p/8463200.html)  
[git命令学习](https://git-scm.com/book/zh/v1/%E8%B5%B7%E6%AD%A5)  

## 模型资源地址
- **Unity-Resources-Particle Pack** *有爆炸, 火焰, 火箭等*
- 游戏蛮牛
- 52素材
- 6m5m
- unity官网
- 微元素


## Git LFS

lfs需要先装好再建仓库, 已经建好的则需要删掉重建

[Git branch -r 无法获取远程分支](https://www.cnblogs.com/leodaxin/p/8569061.html)

Git LFS on github.com does not currently support pushing LFS objects to public forks. GitHub Enterprise does support this behavior. -> [can not upload new objects to public fork](https://github.com/git-lfs/git-lfs/issues/1906)



git lfs can not push fork, so I create a new one

Google BulletTIme Git Youtube



**由于对git lfs不熟悉, 当前代码和设置不是最新版, 但release是最新版**