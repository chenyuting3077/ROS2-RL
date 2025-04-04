# ROS2-RL
傳遞強化學習的感動

# 課後筆記
- 時序差分算法 (Temporal difference learning, TD learning)
- 多臂老虎機問題 (multi-armed bandit, MAB)

## 時序差分算法(Temporal difference learning, TD learning)
當無法寫出馬可夫決策過程的狀態轉移概率時， Agent 透過與 enviroment 進行互動，透過採樣到的數據來學習被稱為，無模型強化學習 (model-free reindforcement learning)。

無模型的強化模型兩大經典演算法， Sarsa 和 Q-learning 都是基於時序差分演算法(Temporal difference)。

on-policy: 更新的 agent 與環境互動的 agent 是同一個
off-policy: 更新的 agent 與環境互動的 agent 不是同一個

### Q-Learning


### DQN (Deep Q-Learning)

## To-do
- [ ] 創建一個繁體中文強化學習網站
  

## 參考資料
[动手学强化学习](https://hrl.boyuai.com/)

[伯宇人工智能學院](https://www.boyuai.com/elites/course/xVqhU42F5IDky94x/video/6uJI-xIs4wqMU56NSbZRB)

[深度強化式學習](https://www.books.com.tw/products/0010886296?srsltid=AfmBOoqH7m7JrI0DiHocibmGptV7erGaJTgngEdrMVUx5gKSM6Q8YEeL)

[掌握机器人强化学习技术](https://app.theconstruct.ai/courses/mastering-reinforcement-learning-for-robotics-286/)