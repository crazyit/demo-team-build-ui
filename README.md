# Tag Battle Crusher

操作非常简单的快节奏 3v3 组队横版无双式乱斗游戏。



## 操作方式

游戏灵感来自《全民无双》的简易操作模式，包括以下操作：

点击屏幕空白区域切换角色移动方向，角色前进时有敌人进入攻击范围时就会自动进行攻击，自动攻击包括4段，每段攻击结束后如果攻击范围内还有敌人就会进行下一段攻击。通常第四段攻击会比较强力。
每段普通攻击的收招阶段可以点击相反移动方向取消，取消之后一段时间内如果再次满足普攻条件，会继续进行下一段攻击。
点击屏幕右边的技能按钮，可以消耗能量，发动大招，大招无法取消，大招使用后有一段时间的cd
按住屏幕进入蓄力模式，蓄力结束后可以发动强力攻击
双击屏幕进行紧急闪避，会向点击的方向快速移动并有一小段无敌时间
点击屏幕左边的角色头像可以切换人物，出招和受创硬直过程中无法立刻切换，会在第一个可操作帧进行切换。
点击屏幕右边候补角色的技能可以发动该候补的大招作为援护攻击。


## 角色分类和技能

每个角色有不同的攻击和技能属性，按照其功能分为以下几类：

- 刺客型：高攻击低防御，关键技能击中对方可能造成必杀
- 坦克型：高防御，具有各种硬体效果，用于接近对方并控制住对方，或拖延时间让本方核心回血或回复技能cd
- 射手型：远程攻击消耗对方，近身时缺少作战能力
- 辅助型：大招和被动技能用于回复或强化队友
- 诅咒型：攻击力低，攻击可能对对方造成不良状态，大招常用于削弱敌人

每个角色有一个主动技能（大招和援护），外加两个被动技能，被动技能范例：

- 提高自身闪避率
- 提高自身暴击率
- 提高对 AOE 的防御
- 每次攻击会给对方上一个标记，每三次标记爆炸造成伤害
- 加速光环
- 生命回复光环
- 单体吸血，吸血光环（在候补时队友吸血）
- 自身阵亡时强化队友攻击力
- 队友阵亡时强化自身速度和攻击力

## 组队策略

战斗规则是己方队伍三人全部阵亡则输掉比赛，因此有以下几种组队策略：

- 大将 辅助 辅助：靠一个英雄从头打到尾的战略，辅助英雄提供光环和技能支援，保证第一个英雄不会死掉
- 副将 大将 辅助：副将首先出战用于试探、消耗和积攒能量，能量攒满时换上主将打击敌人
- 副将 副将 大将：大将需要技能强化或队友牺牲强化时，前面两个队员用来拖延时间到大将登场满能量强化后清场
- 大将 x 3：三个单兵作战能力强角色的组队，靠个人能力硬吃对方

## 养成元素

包括角色收集，角色培养（主动和被动技能升级）

## 画面和表现：

使用 spine 制作角色动画，攻击效果以序列帧的刀光效果为主
受击、飙血使用序列帧制作
大招效果使用序列帧和粒子结合制作