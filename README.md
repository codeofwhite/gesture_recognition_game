# 手势飞机大战游戏——gesture_recognition_game
## 用户操作说明
### 4.1	系统组成
本项目大致上由四个模块组成：
（1）手势识别模块：手势捕捉和分析
（2）游戏模块：设计游戏逻辑
（3）登录系统：记录用户数据
（4）交易系统：进行飞船升级

### 4.2	游戏模块

#### 4.2.1手势识别

以下是各个手势的识别：
#### 4.2.2漫游功能
（1）这一个模式用户将在星海中漫游，在路上会碰到陨石的阻拦，击碎陨石可获得分数。
（2）左右手的剪刀是控制飞机变小。
（3）左手拳头或比赞控制飞机的镭射攻击。
（4）右手握拳或比赞是发射普通子弹。
（5）当飞机生命值没了的时候，将会扣除生命数，进入无敌的状态一段时间。
（6）当飞机吃到时间道具的时候进入无敌状态一段时间。
（7）当飞机吃到闪电的时候，右手的射击模式变为双射，连续捡到变为三射。
（8）若飞机吃到X2道具，分数将会翻倍。
（9）若飞机吃到护盾道具，将会恢复10点血量。
（10）若生命数归零，结束游戏。
（11）若玩家点击右上角的叉叉，将会不保存游戏中获得的分数（战斗到死为止）。
 
#### 4.2.3挑战（PVE）功能
这一个模式用户将挑战本游戏的boss，击败它，然后获得胜利。
（1）这是第一个boss状态，为外星荒野主题配色。
（2）这是第二个boss状态，为蓝色幽深的游戏配色。
（3）这是第三个boss状态，为圣洁的主题配色。
（4）玩家左手one切换到hero形态，左手剪刀回血，paper手势回到原本的状态。在hero模式下玩家不可射击。
（5）玩家右手one切换到queen形态，右手剪刀变小，paper返回原本的状态。注意：在queen的缩小状态下不可设计，在queen的普通状态下可以射击，但子弹对boss的伤害会降低。
（5.2）当玩家死亡后，在原地变成墓碑，然后按任意键退出游戏。
（6）若玩家打败boss后的效果，boss原地起坟。
 
当然中途退出也不计入分数（你也需要战斗至死为止）。
### 4.3	登录模块
#### 4.3.1登录功能
（1）用户可登录自己的账号进行游玩，保存游玩纪录。
（2）若输入错误的密码，显示错误信息。
（3）若没有注册此账号，则跳转到注册页面。
#### 4.3.2	注册功能
（1）用户若没有或想注册一个新的账号，这个模块可以帮到他们。
（2）如果用户操作不当，会出现一些提示信息。

#### 4.3.3	用户主页
（1）包含的内容有：用户获得的总分数，用户自由模式获得的最高分，用户游玩自由模式的场数，用户冒险模式的总胜场。
 
### 4.4	交易模块
#### 4.4.1 升级功能
	（1）可升级的技能有：物品掉落几率，用户移动速度，用户生命值，用户生命数。
 
### 4.5	其他
（1）游戏的主页面展示。
（2）在第一次启动游戏时会有开场动画的展示，讲述了来龙去脉。
（3）游戏主界面上有简单的新手教程，用户可以更具教程自行探索游戏。
（4）点击关于制作者，这里你可以知道有关于我的一些信息。
 
