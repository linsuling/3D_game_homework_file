## 作业要求

有趣 AI 小游戏制作，不限于以下范围：

1. 让事物具有学习功能，经过不同训练可以达到不同效果。如健身达人

2. 利用机器学习或人工智能算法实现学习的创新游戏场景片段

3. 利用在线语音识别或人脸识别等AI服务的创新游戏场景片段

## 游戏说明

地图为简单的迷宫。玩家的目标是到达红色和黄色的两个地点获取积分后，达到绿色目的地，游戏结束。

玩家有两种前进方式：

一种是键盘读取wsad表示前进后退左移右移。

另一种是鼠标点击某一地点，游戏AI规划前进路线并移动人物。

本游戏用到的AI部分即为NavMeshAgent组件。

## 实验步骤

创建一个平面和一些立方体表示迷宫的墙，将它们的标签设置为Ground，勾选Static。开启navigation-bake。

胶囊体增加Nav Mesh Agent组件。

放置红黄绿色目标。

胶囊体挂载脚本ClinkBehaviourScript.cs，指定GameObject为放置的三个目标。

创建空物体挂载脚本IMGUIScript.cs，用于显示当前分数和游戏胜利的标识。

## 游戏运行

创建空项目，替换Assets。

游戏效果如下：

<img src="https://github.com/linsuling/3D_game_homework_file/blob/main/%E4%BD%9C%E4%B8%9A9_AI%E5%B0%8F%E6%B8%B8%E6%88%8F/pic1.png" />
