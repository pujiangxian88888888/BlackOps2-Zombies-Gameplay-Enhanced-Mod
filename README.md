# 使命召唤：黑色行动2 僵尸模式 游戏性增强模组

## 作者: MizugakiISla 原作者：Jbleezy

[作者Bilibli](space.bilibili.com/24929681)

# 如何安装mod？
* 首先前往release模块下载编译好的游戏mod。
* 你需要在steam上拥有使命召唤：黑色行动2，**并完整安装包括战役，多人与僵尸在内的所有部分。**
* 前往https://plutonium.pw/,下载启动平台，按照网站教程配置好游戏，找到%AppData%\Local\Plutonium\storage\t6\mods这个文件夹，将下载好的mod文件放入。
* 启动游戏装载mod即可游玩。

# 如何编译？
* 如果你只是改动了 attachmentunique, maps, images, scripts, ui, ui_mp和weapons这7个文件夹中的内容，你只需要选中这七个文件夹，将它们打包为RAR压缩文件，**并设置压缩等级为0（仅存储）**，然后改名为mod.iwd
* 如果你要改动zone以及其他文件，按照下列方法执行：
* 下载编译器：https://github.com/Laupetin/OpenAssetTools/releases
* 右键打开源代码中的build.bat，找到下列两行：
    ```
    set OAT_GAME="K:\cod"
    set OAT_BASE="K:\oat"
    ```
* 将第一个路径改为你的黑色行动2游戏根目录，将第二个路径改为你下载的编译器的根目录。
* **警告：如果你使用的是非英文版的windows系统，则这两个文件夹必须置于磁盘分区的根目录下，且文件夹名只能包含英文字母，否则可能导致无法编译！你可以将steam中的BO2本地文件夹复制到别处并重命名。**
* 运行此BAT文件，将得到的ff, sabs, sabl与iwd文件置于你的mod文件夹。
 
# 改动记录
* 没有改动的原作者的特性不会在此提及。只会提及新增的改动

## HUD与UI
* 加载界面左上角的地图名，地点提示，游戏模式已被替换。
* 加载界面第三行的模式文本改为地图剧情发生的时间。
* 迁徙的地点提示从“北半球”改为“美国华盛顿州汉福德区”
* 核弹镇的地点提示从“美国内华达州”改为“美国内华达州爱德华营地”
* 高楼的地点提示从“第22省”改为“中国上海浦东新区”
* 埋葬的地点提示从“主要板块”改为“安哥拉纳米贝省”

## 玩家
* 玩家在被复活后会被僵尸无视五秒

## 敌人AI

### 普通僵尸
* 血量上限降至30000
* 对玩家的伤害由50提升至60

### 迁徙抱脸怪
* 抱脸怪已被彻底移除

## 武器
* 大部分武器的弹匣容量与弹药携带量已被增强。以多人模式的同款武器为基准，未升级版的弹匣容量小于多人同款武器或升级版的弹匣容量小于多人同款武器配备加长弹匣的，将统一增加到与多人模式相同。多于多人模式数值的则保持不变（例如，R870霰弹枪弹匣容量已从6增加到8）
* 除了起源，其他所有地图的初始武器已被替换为Tac-45
* 所有战役旧时间线武器，如M1911,MP5等已被移除
* 所有原版BO2僵尸地图独占武器，例如监狱的死亡机器，高楼埋葬的AN94，已被添加到所有地图
* 所有只在多人和战役出现的武器，例如peacekeeper，Titus6等，已被添加到所有地图
* 取消了原作者Jbleezy对武器的所有削弱，例如，AN94的弹药携带量已从240恢复到300

### 手枪
* 移除: M1911, Python, B23R W/Extended Clip
* 新增: Tac-45

#### Tac-45
* 未升级版: 弹匣容量增加到10

#### Five-seven Dual Wield
* 未升级版: 弹匣容量增加到20
* 升级版: 弹匣容量增加到26
* 在起源中玩家可以在购买单持57的地方购买双持57的弹药

#### KAP-40
* 未升级版: 弹匣容量增加到15
* 升级版: 弹匣容量增加到20

### 步枪
* 移除: M14, Colt M16A1, FAL, AK47, Galil
* 新增: SWAT-556, FAL-OSW

#### AN-94
* 售价从1500恢复到1200
* 未升级版: 弹药携带量从240恢复到300
* 升级版: 弹药携带量从480恢复到600

#### M27
* 升级版: 弹匣容量增加到40

#### M8A1
* 未升级版: 弹药携带量从192提升到256
* 升级版: 开火模式从四连发改为全自动

#### MTAR
* 升级版: 弹匣容量增加到40

#### SMR
* 未升级版: 弹匣容量恢复到20
* 升级版: 弹药携带量恢复到420
* 升级版: 弹匣容量增加到26

#### SWAT-556
* 未升级版: 弹药携带量增加到210
* 升级版: 弹匣容量增加到40

### 微型冲锋枪
* 移除: MP5, AK74u, UZI, AK74u W/Extended Clip, MP40 W/Adjustable Stock
* 新增: MP7, MSMC, Vector K10, Peacekeeper

#### Chicom CQB
* 未升级版: 弹匣容量恢复到40
* 未升级版: 弹药携带量增加到252
* 升级版: 弹匣容量增加到48
* 升级版: 弹药携带量增加到336
* 升级版: 开火模式从四连发改为全自动
* 升级版: 移除快慢机配件

#### MSMC
* 未升级版: 弹药携带量增加到210
* 升级版: 弹匣容量增加到40

#### Peacekeeper
* 替换监狱的UZI墙壁购买
* =升级版武器重命名为"Writ of Shamash"(与黑色行动3，4相同)

#### PDW-57
* 升级版: 弹匣容量增加到65

#### Skorpion EVO
* 升级版: 弹匣容量增加到42

#### Vector K10
* 未升级版: 弹匣容量增加到36
* 升级版: 弹匣容量增加到48

### 轻机枪
* 移除: RPD
* 新增: MK 48, QBB LSW

#### Mk 48
* 升级版: 弹匣容量增加到135

#### QBB LSW
* 未升级版: 弹匣容量降低到75
* 升级版: 弹匣容量降低到100
* 升级版: 弹药携带量提升到700

### 狙击步枪
* 移除: Barrett M82A1
* 新增: XPR-50
* 爆头伤害加成从8倍恢复为10倍

#### Ballista
* 未升级版: 弹匣容量降低到7

#### DSR 50
* 未升级版: 弹匣容量增加到5
* 升级版: 弹匣容量增加到7

#### XPR-50
* 未升级版: 弹匣容量增加到8
* 升级版: 弹匣容量增加到11

### Shotguns
* 移除: Olympia

#### S12
* 未升级版: 弹药携带量提升到100
* 升级版: 弹匣容量增14

#### M1216
* 未升级版: 弹药携带量提升到128

#### Remington 870 MCS
* 未升级版: 弹匣容量增加到8
* 升级版: 弹匣容量增加到11

#### KSG
* 未升级版: 弹药携带量提升到112
* 升级版: 弹药携带量提升到140

### 特殊武器

#### Crossbow
* 在起源中移除，因为游戏会崩溃

#### Titus-6
* 升级版: 现在爆炸投射物发射后可以吸引僵尸

### 近战武器
* 所有手持式近战武器已被移除，因为它们会占用装备槽位

#### 银勺子
* 伤害恢复到1100

#### 金叉勺
* 伤害恢复到10000

### 奇迹武器与装备
* 现在无需花费金钱购买

#### Jet Gun
* 现在是主武器而非装备
* 降低过热速度
* 提升冷却速度
* 能牵引并杀死更远的敌人

#### 盾牌
* 盾牌受损能在工作台修复
* 双倍盾牌耐久度，与黑色行动3相同

### 战术手雷

#### 猴子炸弹
* 监狱新增猴子炸弹

#### EMO手雷
* EMP手雷停用汽水机与强化机的时间从90秒降低到10秒

#### 烟雾弹
* 移除

## 汽水技能

### 厚血
* 降低生命恢复前的延迟，并提升回复速率

### 快速复活
* 还原为官方原版逻辑
* SOLO模式可以购买6次

### 快跑
* 降价到2000
* 在迁徙中（不包括生存模式）拥有快跑可以使玩家无限奔跑

## 强化机
* 武器升级后获得更多配件

## Powerups
* 掉落几率恢复到3%

### Max Ammo
* 拾取后会恢复玩家武器弹匣内的弹药

### 锤子
* 重新加入游戏。拾取后能修复玩家盾牌

### Zombie Blood
* 还原为官方默认逻辑

## 地图与彩蛋
* 所有地图的主线菜单现在均可单人完成

### 核弹镇
* 现在SOLO模式下首个掉落的技能将会是快速复活
* 汽水机将每三回合掉落一次，而不再是五回合

### 迁徙
* 当电源关闭或者汽水机被EMP停用时，玩家身上的技能汽水不再被停用

### 高楼
* 电梯系统现已完全重做。玩家可随时呼叫任意电梯到达玩家所在位置，除非得到玩家指令电梯将不会移动。当玩家站在电梯顶上时可以命令电梯上升或者下降。

### 埋葬
* 所有有关亚瑟和武器绘制的逻辑已被重置为官方默认。

### Origins
* 马西斯无人机拾取四个奖牌的彩蛋奖励从升级版MG08改为升级版死亡机器
* 完成115个爆头击杀后奖励的升级版STG44或者加利尔已被替换为升级版M27或者AN94
* 挖掘骷髅堆可能出现的MP40,STG44，阔剑地雷，AK74U已被替换为MP7,peacekeeper或M27

# How to install?
* Download the mod from the **Release**(not source code)
* you need own call of duty:black ops 2 on steam，**and install the full game include campaign,multiplayer and zombies**
* navigate to https://plutonium.pw/, then find the folder located in %AppData%\Local\Plutonium\storage\t6\mods,put all files in it.
* Launch the game, load the mod and enjoy.

# How to compile?
* if you just change **attachmentunique, maps, images, scripts, ui, ui_mp and weapons** folder，Save it as .rar file **with compression level 0** and then rename the rar file to mod.iwd
* if you need to modify the zone and other files, follow the steps:
* Download compilerfrom https://github.com/Laupetin/OpenAssetTools/releases
*right click and open build.bat,find there 2 lines
    ```
    set OAT_GAME="K:\cod"
    set OAT_BASE="K:\oat"
    ```
* set the 1st path to your game root,2nd path to your compiler.
* **Warning: If you are using a non-English version of windows, the two folders must be placed in the root directory of the disk partition, and the folder name can only contain English letters, otherwise it may cannot be compiled! You can copy the BO2 local folder in steam and rename it elsewhere.**
* Run this BAT,and put all the ff,sabl,sabs files to your mod folder.

# Black Ops2 Zombies Gameplay Enhanced

## Created by: MizugakiISla,Forked From Jbleezy

# Change Notes
* The existing changes made by the original author will not be mentioned here. Only the new changes added to this project will be discussed

## HUD and UI
* The loading image text are all replaced.
* The loading image 3rd text line are replaced to map's timeline.
* Tranzit's location hint is changed from "NORTHERN HEMISPHERE" to "Hanford Site, Washington State, U.S.A."
* Nuketown's location hint is changed from "NEVADA, U.S.A" to "Camp Edward, NEVADA, U.S.A."
* Die Rise's location hint is changed from "PROVINCE 22" to "PUdong new district, ShangHai, China"
* Buried's location hint is changed from "Primary plante" to "Namibe, Angola"

## Players
* Ignored by zombies for 5 seconds after being revived

## Enemy AI

### Zombies
* Health capped at 30000
* Increased player damage from 50 to 60

### Denizens
* Denizens are completely removed from the game

## Weapons
* Most weapons' clipsize and ammo stock are increased. Based on the same weapons in multiplayer, if the clip size of an un-upgraded weapon is smaller than that of the same weapon in multiplayer or if the clip size of an upgraded weapon is smaller than that of the same weapon in multiplayer with the extended clip , it will be uniformly increased to the same value as in multiplayer. If it is larger than this value, it will remain unchanged.(e.g. the R870 shotgun's clipsize has been increased to 8 from 6,the upgraded version has been increased to 11 from 10 )
* Besides Origins, All other maps' player starting weapon has been changed to Tac-45
* All the campaign old storyline weapons(e.g. Galil, M1911, MP5) are removed from the game
* All the map-exclusive weapons(e.g. SCAR-H in origins, AN-94 in Die-Rise and Buried) are added in all maps
* All the multiplayer and campaign exclusive weapons are added in all maps
* Canceled all weapons' nerf from Jbleezy's original mod, For example the AN-94's ammo stock has been restored from 240 to 300, and the price has been restored from 1500 to 1200

### Pistols
* Removed: M1911, Python, B23R W/Extended Clip
* Added: Tac-45

#### Tac-45
* Unupgraded: increased clipsize from 8 to 10

#### Five-seven Dual Wield
* Unupgraded: increased clipsize from 15 to 20 
* Upgraded: increased clipsize from 20 to 26 
* In Origins, you can now purchase ammo from Single Five-seveN's wallbay

#### KAP-40
* Unupgraded: increased clipsize from 12 to 15
* Upgraded: increased clipsize from 15 to 20

### Assault Rifles
* Removed: M14, Colt M16A1, FAL, AK47, Galil
* Added: SWAT-556, FAL-OSW

#### AN-94
* Restored weapon cost from 1500 to 1200
* Unupgraded: Restored stock ammo from 240 to 300
* Upgraded: Restored stock ammo from 450 to 600

#### M27
* Upgraded: Increased clipsize from 30 to 40

#### M8A1
* Unupgraded: increased stock ammo from 192 to 256
* Upgraded: Change fire mode from 4-Round-Burst to Full Auto

#### MTAR
* Upgraded: Increased clipsize from 30 to 40

#### SMR
* Unupgraded: Restored clipsize from 10 to 20
* Upgraded: decreased stock ammo from 200 to 420
* Upgraded: increased clipsize from 20 to 26

#### SWAT-556
* Unupgraded: increased stock ammo from 150 to 210
* Upgraded: increased clipsize from 30 to 40

### Submachine Guns
* Removed: MP5, AK74u, UZI, AK74u W/Extended Clip, MP40 W/Adjustable Stock
* Added: MP7, MSMC, Vector K10, Peacekeeper

#### Chicom CQB
* Unupgraded: restored clipsize from 36 to 40
* Unupgraded: increased stock ammo from 120 to 252
* Upgraded: increased clip ammo from 40 to 48
* Upgraded: increased stock ammo from 200 to 336
* Upgraded: Change fire mode from 4-Round-Burst to Full Auto
* Upgraded: Removed Select-Fire Attachment

#### MSMC
* Unupgraded: increased stock ammo from 150 to 210
* Upgraded: increased clipsize from 30 to 40

#### Peacekeeper
* Replaced UZI wallbuy in Mob of the Dead
* Renamed the upgraded weapon to "Writ of Shamash"(Same as BlackOps 3 and 4)

#### PDW-57
* Upgraded: changed weapon name from "57000" to "5700"
* Upgraded: increased clipsize from 50 to 65

#### Skorpion EVO
* Upgraded: changed attachment from Reflex Sight to Fast Mag
* Upgraded: increased clipsize from 40 to 42

#### Vector K10
* Unupgraded: increased clipsize from 24 to 36
* Upgraded: increased clipsize from 36 to 48

### Light Machine Guns
* Removed: RPD
* Added: MK 48, QBB LSW

#### Mk 48
* Upgraded: increased clip ammo from 100 to 135

#### QBB LSW
* Unupgraded: decreased clipsize from 125 to 75
* Upgraded: decreased clipsize from 125 to 100
* Upgraded: increased stock ammo from 625 to 700

### Sniper Rifles
* Removed: Barrett M82A1
* Added: XPR-50
* Restored headshot damage multipier from 8 to 10

#### Ballista
* Unupgraded: decreased clipsize from 8 to 7

#### DSR 50
* Unupgraded: increased clipsize from 4 to 5
* Upgraded: increased clipsize from 5 to 7

#### XPR-50
* Unupgraded: increased clipsize from 5 to 8
* Upgraded: increased clipsize from 8 to 11

### Shotguns
* Removed: Olympia

#### Remington 870 MCS
* Changed weapon cost from 900 or 1500 to 1200 on all maps

#### S12
* Unupgraded: increased stock ammo from 40 to 100
* Upgraded: increased clipsize from 10 to 14

#### M1216
* Unupgraded: increased stock ammo from 48 to 128

#### Remington 870 MCS
* Unupgraded: increased clipsize from 6 to 8
* Upgraded: increased clipsize from 10 to 11

#### KSG
* Unupgraded: increased stock ammo from 56 to 112
* Upgraded: increased stock ammo from 84 to 140

### Specials

#### Crossbow
* Removed on Origins because it will crush the game

#### Titus-6
* Upgraded: The projectile mode now can attract Zombies

### Melee Weapons
* All the held melee weapons have been remove because they occupy the actionslot

#### Silver Spoon
* Restored damage from 1000 to 1100

#### Golden Spork
* Restored damage from 5000 to 10000

### Wonder Weapons and Equipments
* Now do not need money to purchase

#### Jet Gun
* It's now Primary weapon, Not equipment
* decreased the over-heating rate
* increased the cooling down speed
* Can drag and kill enemy in further distance

#### Zombie Shield
* Can now be fixed if it's damaged at workbench
* The shield durability is twice than original, Same as BlackOps 3

### Tactical Grenades

#### Monkey Bomb
* Added in Mob of the Dead

#### EMP Grenade
* Disable the Perk vending machine and Pack-a-Punch from 90 seconds to 10 seconds

#### Smoke Grenade
* REMOVED

## Perks
* Added high qualty perk icons to all maps
* Removed perk limit
* Removed blur after drinking
* No longer deactivated if the perk machine is powered off
* Perk order on HUD is restored whenever perks are restored to the player
* Perk order on HUD is shown correctly when spectating

### Jugger-Nog
* Shorter the delay before health regeneration and increased the health regenerate speed

### Quick Revive
* Restored to default logic
* In solo game, the player can now buy it 6 times instead of 3

### Speed Cola
* Aim twice as fast
* Switch weapons twice as fast
* Throw grenades twice as fast

### Double Tap
* Removed shooting 2 bullets for every shot
* Increases bullet damage by 50%

### Stamin-Up
* Restored cost from 2500 to 2000
* Move 10% faster (normally only sprint 10% faster)
* In tranzit classic mode(Not include survival mode), Stamin-Up can now make player unlimited sprint.

## Pack-a-Punch
* The weapon will aquire more attachments when upgraded.

## Powerups
* Restored drop rate from 2% to 3%

### Max Ammo
* Sets heat weapons to 0% heat
* Will refill player weapons' clip after been picked up

### Carpenter
* Re added to the game. will repair players' shield when picked up

### Fire Sale
* Added on Tranzit and Die Rise

### Zombie Blood
* Reset to default logic

## Persistent Upgrades
* Re added to the game and always avaliable

## Maps and Quests
* All maps' main quests are now can be finished in SOLO.

### Nuketown
* Restored the first-dorpped perk. it always will be Quick Revive in solo mode
* Perk will be dropped by every 3 rounds, instead of 5

### Tranzit
* players' perks are won't be disabled if the power is turned off, or the vending machine is EMPed.

### Die Rise
* Elevator system are completely remaked: You can call the elevator at anytime, the elevator will not move unless you call it from the other place. When you're standing on top of the elevator you can command it to go up or down

### Buried
* The gameplay about Arthur and barrier are all reset to default

### Origins
* The Maxis drone "medal-pick-up" Quest reward are replaced by upgraded death machine
* The 115 headshots reward, the upgraded Galil and Stg44 are replaced by upgraded M27 and AN-94
* The dig award, claymore mine, ak74u, mp40 and stg44 replaced by mp7, peacekeeper and M27