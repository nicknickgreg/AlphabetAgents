# AlphabetAgents
Rag doll physics simulation of letters of the alphabet using ml-agents.

## Training

The training models are located at Assets/models/

In order for training models to be created inside the Unity Project run training commands from inside the Assets/ directory.

When training in the editor:
`mlagents-learn ../../config/trainer_config.yaml --run-id=Alphabet_00 --train`


To run tensorboard use: `tensorboard --logdir=summaries` then open http://localhost:6006/

More info: https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-ML-Agents.md

## Character Rigs

Each leter can have multiple heads and feet with one set of hips.

A head is a bone at the top of the character. In a case like a 'T' or 'F' where a top bone branches, the the head bone is the bone that is aligned to either the left or the center of the branching.

The hips is the bone closest to the middle of the charcter and from which all other bones extend from, in the case of a character like a 'U' the bone at the left is chosen as the hips.

A foot is just like a head, only for the bottom of the character.

### A
* 1 head
* 1 hips
* 2 feet

### B
* 1 head
* 1 hips
* 1 foot

### C
* 1 head
* 1 hips
* 1 foot

### D
* 1 head
* 1 hips
* 1 foot

### E
* 1 head
* 1 hips
* 1 foot

### F
* 1 head
* 1 hips
* 1 foot

### G
* 1 head
* 1 hips 
* 1 foot

### H
* 2 heads
* 1 hips
* 2 feet

### I
* 1 head
* 1 hips
* 1 foot

### J
* 1 head
* 1 hips
* 1 foot

### K
* 2 heads
* 1 hips
* 2 feet

### L
* 1 head
* 1 hips
* 1 foot

### M
* 2 heads
* 1 hips
* 2 feet

### N
* 2 heads
* 1 hips
* 2 feet

### O
* 1 head
* 1 hips
* 1 foot

### P
* 1 head
* 1 hips
* 1 foot

### Q
* 1 head
* 1 hips
* 1 foot

### R
* 1 head
* 1 hips
* 2 feet

### S
* 1 head
* 1 hips
* 1 foot

### T
* 1 head
* 1 hips
* 1 foot

### U
* 2 heads
* 1 hips
* 1 foot

### V
* 2 heads
* 1 hips
* 1 foot

### W
* 2 heads
* 1 hips
* 2 feet

### X
* 2 heads
* 1 hips
* 2 feet

### Y
* 2 heads
* 1 hips
* 1 foot

### Z
* 1 head
* 1 hips
* 1 foot
