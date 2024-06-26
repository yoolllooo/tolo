# Path Planning and Control Simulation

## 项目概述
本项目实现了基于A*和RRT算法的路径规划，以及Pure Pursuit和Stanley方法的路径跟踪控制仿真。项目使用Python编写，结合了numpy和matplotlib进行数据处理和可视化。

## 功能特性
- **A*路径规划**：使用A*算法从起点到终点生成最优路径。
- **RRT路径规划**：使用RRT算法从起点到终点生成随机树路径。
- **Pure Pursuit控制**：基于Pure Pursuit算法进行路径跟踪控制。
- **Stanley控制**：基于Stanley算法进行路径跟踪控制。
- **路径仿真**：使用matplotlib进行路径规划的动态可视化。

## 文件结构
- `hw.py`：主程序文件，包含所有路径规划和控制算法的实现。
- `main.py`：代码运行会显示所有探索点。
- `README.md`：项目说明文档。

## 安装和运行
### 前置条件
- Python 3.10
- numpy
- matplotlib

### 运行步骤
1. 在命令行中运行以下命令启动程序：
    ```bash
    python hw.py
    python main.py（可以不运行main，main所生成的路径和hw相同）
    ```

2. 得到结果：hw.py文件运行后会得到四个图，分别是两种路径规划算法下的两种控制算法的路径。main.py文件运行后可见两种路径规划算法的具体探索点。
