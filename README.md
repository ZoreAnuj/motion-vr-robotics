# Motion-VR-Robotics: Transferring Human VR Motion to Robotic Manipulation

This project adapts human VR motion data to train robotic manipulation policies, enabling more natural and dexterous robot control. It builds upon the MotionTrans research to explore how human demonstrations can enhance robotic learning in real-world tasks.

## Key Features
- Processes human VR motion sequences for robotic policy training
- Implements motion-level learning from human demonstrations
- Transfers dexterous manipulation skills to robotic systems
- Compatible with standard robotic simulation environments

## Tech Stack
- Python
- PyTorch
- OpenAI Gym
- MuJoCo

## Getting Started
```bash
git clone https://github.com/zoreanuj/motion-vr-robotics.git
cd motion-vr-robotics
pip install -r requirements.txt
python train.py --config configs/default.yaml
```