# A Mulit-Agent Reiforcement Learning model to play chess

Based on code from [PettingZoo and Tianshou](https://pettingzoo.farama.org/tutorials/tianshou/advanced/)

## Pre-Trained Agents

You can watch a number of pretrained agents play against each other.

**Note:** `mix_train.pth` and `mix_train_adv.pth` can only play against each other due to architecture differences
`
### `Random.pth`
Agent trained for 60 epochs against player that plays random moves

### `self_play.pth`
Agent trained against itself for 60 epochs

### `mixed_train.pth`
Agent trained with both self play and against random players for 75 epochs

### `mix_train.pth`
Same as `mixed_train.pth` but model has two layers with 256 neurons. Trained for 60 epochs

### `mix_train_adv.pth`
Same as `mix_train.pth` but trained for 100 epochs