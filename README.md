# 15971_TwoRobot

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/15971_TwoRobot/blob/main/15971_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , dfs

## What was the key point and the hard part?

At first , I try to find all cost starting from robot1's location and robot2's location.

After that , I tried to find the first robot's location , cost + second robot's cost to reach near location.

This have some problem when N == 1 and robot1's location == robot2's location , it succeeded.

The better algorithm is to save the path and cost robot1 to reach robot2's location.

After that , find the max cost and subtract it to sum of all cost will be the answer.

This algorithm is working because there is only one way to reach some nodes from some node.

If there is many way, I think I have to use dijkstra at starting point and end point and find the min value.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
