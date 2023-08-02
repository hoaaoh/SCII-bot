# SCII-bot
Reinforcement learning on StarCraft II

## Preliminaries
- Make sure the Python3 version is 3.7
- Install PySC2 following this [link](https://github.com/deepmind/pysc2)
- If you're running it in Ubuntu, do
    ```sh
    pip3 uninstall pygame
	pip3 install pygame==1.9.6
    ```


## Top core abilities
### Terran
1. Marines vs Lurker (With Limited Resource of k-Scans)
  - Make it happen by programming
  - Make it happen by machine learning
  - Adversary Attacks: Lurker vs Marines instead (GAN)

2. Marines Walking Attack

### Protoss
2. Train Warp Prism + High Templar

### Zerg
1. Train Cross Air Drop
  - Overlord + Baneling
2. Train Rectangle Baneling

### [Unit Translation](https://gist.github.com/chusiang/ca48f6a437234413e348b6ef2bcbf6d4)


### Script to run
- Agent1: SCVs mines until Terran has one Raven and two Marines.
- Agent2: Drones mines until Zerg has two Lurkers.
