# Hi, I'm Vansh Gala

Robotics M.S. student at **Arizona State University** (GPA 3.7, May 2027) and former embedded robotics systems engineer. I build robot software end to end: controls, motion planning, state estimation, perception, embedded firmware and automotive CAN, and I test it the way products are tested.

**Open to:** robotics, embedded and autonomy roles: co-op (Jan to May 2027) or full-time from May 2027.

[LinkedIn](https://www.linkedin.com/in/vansh-gala-080295233) · vgala1@asu.edu · Tempe, AZ

## Featured projects

| Project | Result | Stack |
|---|---|---|
| [EV Battery ECU Network on CAN](https://github.com/vansh0906/ev-can-ecu-sim) | BMS + VCU in embedded C with DBC signals, CRC/counter E2E checks and UDS over ISO-TP; 15/15 fault-injection SIL tests in CI | C99, CAN, ISO-TP, UDS, ESP32 |
| [ROS 2 Path-Tracking Stack in C++](https://github.com/vansh0906/ros2-path-tracker) | LQR held 0.2 cm RMS cross-track error vs 1.3 cm for Pure Pursuit; 11 GoogleTest tests, Docker CI | ROS 2 Humble, C++17, Docker |
| [Error-State Kalman Filter on SO(3)](https://github.com/vansh0906/eskf-imu-gnss) | 15-state ES-EKF fusing IMU + GNSS: 88% lower position error than raw GNSS, NEES-consistent over 20 runs | Python, NumPy |
| [Quadrotor Minimum-Snap + Geometric SE(3) Control](https://github.com/vansh0906/quadrotor-minsnap-se3) | 0.8 cm RMS tracking at 2.5 m/s and 44 deg tilt, 48x better than a small-angle controller; recovers from a 170 deg flip | Python, NumPy, SciPy |
| [Multi-Robot Safety with Control Barrier Functions](https://github.com/vansh0906/multirobot-cbf) | Decentralised CBF-QP safety filter: 720 to 0 collisions in a 16-robot swap | Python, NumPy, SciPy |
| [iLQR vs MPPI Model-Predictive Control](https://github.com/vansh0906/ilqr-vs-mppi) | Race car with tyre dynamics: MPPI 10/10 vs iLQR 9/10 with 40% less grip; iLQR steered 6x more smoothly | Python, NumPy |
| [LLM-Driven Pick-and-Place Robot Arm](https://github.com/vansh0906/dobot-llm-pick-and-place) | Dobot arm runs plain-English commands with ArUco calibration, persistent memory and operator approval | Python, OpenCV, LangChain |
| [Multi-Robot Warehouse Fleet Planner](https://github.com/vansh0906/warehouse-fleet-planner) | Hungarian assignment cut travel 7.3%; space-time A* gave 0 collisions vs 36 for naive paths | Python, NumPy, SciPy |
| [Path Planning Library in C++](https://github.com/vansh0906/cpp-path-planning) | Header-only Dijkstra, A*, weighted A*, RRT, RRT*; A* expanded 72% fewer nodes than Dijkstra | C++17, CMake, CTest |
| [Warehouse Box Detection & Tracking](https://github.com/vansh0906/warehouse-yolo-tracking-ocr) | Fine-tuned YOLO11n: 0.91 mAP50; ByteTrack keeps IDs across frames at ~21 ms/frame | Python, YOLO11, PyTorch |
| [DC Motor Speed Control in C++](https://github.com/vansh0906/dc-motor-pid-cpp) | 1 kHz PID with anti-windup: overshoot cut from 43.6% to 15.0%; 10 unit tests in CI | C++17, CMake, CTest |
| [Robot Localization: EKF vs Particle Filter](https://github.com/vansh0906/robot-localization-ekf-pf) | 0.17 m and 0.23 m RMSE vs 0.84 m dead reckoning; particle filter recovered from kidnapping 10/10 | Python, NumPy |
| [Cart-Pole: LQR vs MPC](https://github.com/vansh0906/cartpole-lqr-mpc) | LQR and MPC balancing an inverted pendulum, with a Kalman filter on noisy sensors | Python, NumPy |

## More

- [arm-ik-motion-planning](https://github.com/vansh0906/arm-ik-motion-planning)
- [path-tracking-controllers](https://github.com/vansh0906/path-tracking-controllers)
- [vg](https://github.com/vansh0906/vg)

## Toolbox

- **Languages:** C, C++17, Python, MATLAB/Simulink
- **Robotics:** ROS 2, Gazebo, LQR, MPC, iLQR/MPPI, SE(3) control, Kalman filters, A*/RRT*, control barrier functions
- **Embedded & automotive:** ESP32, AVR, Raspberry Pi, I2C/SPI/UART, CAN, DBC, ISO-TP, UDS
- **Perception & AI:** OpenCV, YOLO11, PyTorch, LLM agents
- **Engineering:** CMake, GoogleTest, Docker, GitHub Actions CI, sanitizers, KiCad
