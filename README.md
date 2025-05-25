# ROS2 Publisher-Subscriber Demo

This project demonstrates a simple **publisher-subscriber communication** system in ROS 2 using Python. It was built as part of my hands-on learning journey with ROS 2, Docker, and robotics software fundamentals.


## 🧠 What It Does

- `simple_publisher`: Publishes a string message (`Hello ROS2!`) every 0.5 seconds on the topic `/topic`
- `simple_subscriber`: Subscribes to that topic and prints each message to the terminal


## 🛠️ Technologies Used

- ROS 2 Humble
- Python 3
- Docker (Mac M4 with ARM support)
- Colcon Build System


## 🚀 How to Run

### 1. Build the Workspace

```bash
cd ~/ros2_ws
colcon build
source install/setup.bash
```

### 2. Run the Publisher Node (In terminal 1)

```bash
ros2 run pubsub simple_publisher
```

### 3. Run the Subscriber Node (In terminal 2 inside the same container)

```bash
ros2 run pubsub simple_subscriber
```

✅ You’ll see messages being published and received in real time!


## 💬 Why I Built This

This is the first of 10 beginner ROS 2 projects I'm building to solidify my understanding of ROS 2 fundamentals. I'm exploring Perception, RL, and Multimodal Intelligence for Human-Robot Collaboration, and this is my starting point. I’ll be documenting each project in this journey — feel free to follow along!
