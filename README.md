# Qt_test_Snake
## 蛇身：QVector<QPoint>， 存储每个方块的坐标

## 食物：坐标QPoint

## 定时器速度 随分数升高而加快

## 移动：根据当前方向和蛇首坐标，计算蛇头往该方向移动一格的坐标

## 边界/合法性检测： 判断到达的位置 是否碰撞蛇身自己、是否碰撞边框，

## 合法则往QVector首插入该坐标，尾部元素移除，完成前进。

## 如果移动后吃到食物（食物的坐标与蛇头到达的位置相同），则无需移除尾部元素，蛇身增长一格
