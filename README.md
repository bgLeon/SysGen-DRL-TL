# Systematic Generalisation of abstract operators

Source code of `Agent, do you see it now? systematic generalisation in deep reinforcement learning` @ `ALOE ICLR 2022` and 'Systematic Generalisation of Temporal Tasks through Deep Reinforcement Learning' @ 'ALA AAMAS 2021'.

## Installation instructions

This repository requires [Python3.6](https://www.python.org/) with three libraries: [numpy](http://www.numpy.org/), [tensorflow (V2.5)](https://www.tensorflow.org/), and [gym](https://gym.openai.com/). 

## Running example

    python run_experiment.py --visual --mapType=minigrid --syntax=TTL1 --network=PrediNet --mem --seedB=0 --batch_size=512 --cnn_type=cnn

This runs the SA from the main document in the minigrid benchmark.

run_experiment.py contains instructions for each command
