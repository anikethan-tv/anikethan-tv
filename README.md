# Hi, I'm Anikethan 👋

### MSc Robotic Systems Engineering @ RWTH Aachen University, Germany

I develop software pipelines for robotics: **computer vision systems, imitation learning policies, ROS 2 control stacks, and synthetic data generation.** I work where perception meets motion — writing the code that makes robots understand and act on the world around them.

---

## 🤖 Projects

### 🦾 Real-World Robotic Imitation Learning — LeRobot SO-100 Arm
> Trained a robot arm to autonomously pick a specific colored cube from a group, based on a color instruction given by the user.

Assembled and configured the SO-100 robot arm and used teleoperation to record 50 demonstration episodes. Trained and compared two imitation learning policies — **ACT** (behavior cloning baseline) and **SmolVLA** (language-conditioned, goal-conditioned control). SmolVLA achieved higher success rates due to multimodal representation and asynchronous inference.

`Python` `LeRobot` `PyTorch` `HuggingFace` `Feetech SDK` `Weights & Biases`

🔗 [View Repository](#) *(coming soon)*

---

### 🎮 Sensor-Based Control of a 7-DOF Robot Arm — ROS 2
> Built a real-time teleoperation pipeline that maps physical sensor inputs to control a Kinova robotic arm.

Designed and prototyped a custom teleoperation device using ESP8266, MPU6050 IMU (Cartesian end-effector control), a rotary encoder (joint/gripper commands), and an IR sensor (dead-man switch). Implemented custom ROS 2 nodes and validated the pipeline in Gazebo simulation before deploying on a real Kinova arm — demonstrating full sim-to-real transfer.

`Python` `C++` `ROS 2` `MoveIt 2` `Gazebo` `RViz2` `ESP8266` `Arduino`

🔗 [View Repository](#) *(coming soon)*

---

### 👕 T-Shirt Fold Quality Assessment — Computer Vision Pipeline
> Automated quality assessment of T-shirt folding using deep learning — replacing manual inspection with a CV pipeline.

Built an end-to-end pipeline using EfficientNetB0 with a frozen backbone and fine-tuned blocks 4–7. Implemented both a **5-class classification head** (bad → perfect) and a **regression head** predicting a continuous quality score (1.0–5.0). Achieved 80% classification accuracy and RMSE of 0.411 on held-out test data. Part of research work at WZL, RWTH Aachen.

`Python` `TensorFlow` `EfficientNetB0` `OpenCV` `NumPy` `Matplotlib`

🔗 [View Repository](#) *(coming soon)*

---

### 🌐 Synthetic Data Generation — NVIDIA Isaac Sim
> Automated pipeline to generate labeled synthetic image datasets for training computer vision models — removing the need for manual data collection.

Built a YAML-driven pipeline that loads USD assemblies into Isaac Sim, prepares assets as independent parts, randomizes scene parameters, and batch renders labeled images (images + labels + metadata.yaml). Used for generating training data for semantic segmentation models at WZL, RWTH Aachen.

`Python` `NVIDIA Isaac Sim` `Omniverse USD` `YAML`

🔗 [View Repository](#) *(coming soon)*

---

### 🔤 Transformer-Based Machine Translation — Built from Scratch
> Implemented a Transformer model from scratch to understand and apply attention mechanisms for sequence-to-sequence language tasks.

Built the full Transformer architecture in PyTorch including multi-head self-attention, positional encoding, encoder-decoder structure, and training optimizations. Trained for machine translation tasks.

`Python` `PyTorch`

🔗 [View Repository](#) *(coming soon)*

---

### 📊 Machine Learning on Robotic Arm Dynamics
> Modeled the inverse dynamics of a 7-DOF robotic arm using classical ML techniques.

Used regression and clustering to predict joint torques from motion data. Improved accuracy progressively using polynomial features, Radial Basis Functions (RBF), and k-means clustering. Validated using mean squared error across configurations.

`Python` `scikit-learn` `scipy` `NumPy` `Matplotlib` `seaborn`

🔗 [View Repository](#) *(coming soon)*

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Anikethan_T_V-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/anikethan-t-v-a2a188173/)
[![Email](https://img.shields.io/badge/Email-anikethan.thimmanahalli@rwth--aachen.de-D14836?style=flat&logo=gmail)](mailto:anikethan.thimmanahalli@rwthaachen.de)
