# oh-my-color-war
严格来说是一个游戏，目前的想法：<br>
开局4个玩家，在一个nXn的矩阵中，每个玩家都会有一个初始位置，然后每个玩家依次行动，去占领其他格子，每次行动占领一个。<br>
占领的条件如下：对于空白的格子，只要它的上下左右四块里存在你已占领的地方，你就可以占领它。对于非空白，也就是别人已经占领过的格子，则至少需要两个才可以占领。<br>
结束条件：所有空白的格子均被占领或最后一个走的玩家执行了5XNXN次操作。<br>
具体玩法：每个人需要提交自己的js代码，实现这么一个函数，它的参数为<obj,array>，为游戏基础信息以及当前的棋局，函数需要返回一个合法的二维坐标，以表示你想要占领哪个格子，如果坐标非法则表示放弃此次操作。
