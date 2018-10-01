# AlphabetAgents
Rag doll physics simulation of letters of the alphabet using ml-agents.

## Training

The training models are located at Assets/models/

In order for training models to be created inside the Unity Project run training commands from inside the Assets/ directory.

When training in the editor:
`mlagents-learn ../../config/trainer_config.yaml --run-id=Alphabet_00 --train`


To run tensorboard use: `tensorboard --logdir=summaries` then open http://localhost:6006/

More info: https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-ML-Agents.md
