## 欢迎使用WeiRanBot Beta v1.2

当前机器人仍处于**Dev**阶段

详情请关注此页面

### Mojang

`/mojang` 为根指令:

1. `nh|names ID` **查看历史ID**

2. `mc|minecraft` **查看Minecraft JavaEdition销售统计**

3. `dungeon|minecraft_dungeon` **查看Minecraft Dungeon销售统计**

### Hypixel

`/hyp` 为根指令:

1. `info ID` **查看Hypixel个人信息**

1. `wd|watchdog` **查看服务器封禁信息**

1. `g|guild` 为前缀:
   
   `参数1 {Type}` 为固定格式
   
   _`PlayerName player`_ **使用玩家ID查看所在公会信息**
   
   _`GuildName name`_ **使用公会名查看公会信息**

1. `bw|bedwars ID` **查看玩家Bedwars战绩**

1. `sw|skywars ID` **查看玩家Skywars战绩**

1. `a|arcade` 为前缀:

   _`farmhunt|fh ID`_ **查看玩家躲猫猫战绩**

   _`miniwalls|mw ID`_ **查看玩家迷你战墙战绩**  
   
   _`hypsays|simonsays`_ **查看玩家你说我做战绩**
   
1. `mw|megawalls ID` **查看玩家Megawalls战绩**

   _`{Profession}(不支持缩写)`_ **查看玩家指定职业信息**
   
1. `uhc ID` **查看玩家UHC战绩**

1. `sb|skyblock ID` **查看玩家SkyBlock状态**

   _`bound index`_ **绑定存档**
   
   _`list`_ **查看存档列表**
   
   _`skill`_ **查看技能等级**
  
  
#### 使用说明

私聊机器人输入`/api give {群号} {key}`来为自己的群激活使用权限

{key}获取方法:在Hypixel服务器内输入`/api new`新建一个apiKey即可

一个群可以拥有多个{key}，防止中途暴毙

群主 or 管理员可以在群内输入`/hyp api`查看本群各个{key}的状态
