# PPO v DQN

## A Duel at the Limits of Handling

Alberto Guiggiani

Stanford AA228 Fall 2023 - Decision Making Under Uncertainty - Final Project

---

Jupyter Notebook featuring:

* Set-up of the [Gymnasium Car Racing Environment](https://gymnasium.farama.org/environments/box2d/car_racing/)
* Implementation and training of a Proximal Policy Optimization algorithm via [StableBaseline3 API](https://stable-baselines3.readthedocs.io/en/master/modules/ppo.html)
* Implementation and training of a Deep Q-Network Algorithm
* Simulation and benchmarking

### Getting Started

Create and activate a new venv from the provided `requirements.txt` (recommended Python 3.11)

```bash
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

Run and explore the notebook `final_project.ipynb`

Be wary that the training step are time-consuming and are disabled by flags. Weights are provided for quick execution.