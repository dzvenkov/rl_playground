# Reinforcement Learning related training assessments and experiments

Usage:

1) for use with python 3.11 (3.11.9), creating venv is recommended 
`example: path/to/python11 -m venv myvenv`
2) install pytorch in a way that fits your machine (cpu/cuda) from https://pytorch.org/get-started/locally/
`example: pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118`
3) install rest of the dependencis
`example: pip3 install -r ./requirement.txt`

If experiencing problems with installing gymnasium+box2d related to swig, refer to https://stackoverflow.com/questions/76189511/modulenotfounderror-no-module-named-swig-but-swig-is-already-installed (use choco to install swig on Windows)

For reference, requirements_freeze.txt contains requirements freeze from the venv it was authored in

Rach Jupyter notebook contains
   - training of and agent for some gymnasium env (taxi, lunarlander, carrace) using appicable algorithm/method - manual implementation from scratch.
   - visualization with env.render()


### taxi/ - solving "Taxi-v3" RL sample gym environment using Q-Learning

inspired by https://github.com/IvanFernande/taxi-v3-openai-gym

![](taxi/taxi.gif)


### lander_dqn/ - solving "LunarLander-v3" RL sample gym environment using DQN with 

based on: https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html#dqn-algorithm

![](lander_dqn/0209.gif)
