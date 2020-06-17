## Data for Reinforcement Learning Baselines

We provide results for reinforcement learning algorithms.  



### Results

We provide all results in [google drive](https://drive.google.com/drive/folders/199H4y2Rv_GxNWMPE7aspDXMeax8zySkA?usp=sharing) and [baidu drive](https://pan.baidu.com/s/1GOPS095YwZKl4R12MsttBw) (extraction code: 0fph).

##### MuJoCo

![baselines](https://github.com/MIRALab-USTC/Data-for-Reinforcement-Learning-Baselines/raw/master/baselines.png)

* **sac-rlkit:** 
  * code: [rlkit](https://github.com/vitchyr/rlkit) with default hyperparameter setting.
  * Algorithm: [soft actor critic (SAC)](https://arxiv.org/abs/1812.05905). *Haarnoja, Tuomas, et al. "Soft actor-critic algorithms and applications." arXiv preprint arXiv:1812.05905 (2018).*
* **ddpg-rlkit:**
  * Code: [rlkit](https://github.com/vitchyr/rlkit) with default hyperparameter setting.
  * Algorithm: [deep deterministic policy gradient (DDPG)](https://arxiv.org/abs/1509.02971). *Lillicrap, Timothy P., et al. "Continuous control with deep reinforcement learning." arXiv preprint arXiv:1509.02971 (2015).*
* **td3:** 
  * Code: [authors' code](https://github.com/sfujim/TD3) with default hyperparameter setting.
  * Algorithm: [twin delayed deep deterministic policy gradient arglorithm (TD3)](https://arxiv.org/abs/1802.09477). *Fujimoto, Scott, Herke Van Hoof, and David Meger. "Addressing function approximation error in actor-critic methods." arXiv preprint arXiv:1802.09477 (2018).*



### Todo

- [ ] More algorithms and implementations, such as the official implementation of sac.
- [ ] More than ten random seeds for each algorithm.
- [ ] Results for Atari tasks.
