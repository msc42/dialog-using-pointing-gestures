# Interactive Multimodal Robot Dialog using Pointing Gesture Recognition

This repository hosts the code and other resources for reproducing the experiments from our ECCVW 2022 paper ["Interactive Multimodal Robot Dialog using Pointing Gesture Recognition"](#TODO). Abstract:

> Pointing gestures are an intuitive and ubiquitous way of human communication and thus constitute a crucial aspect of human-robot interaction.
However, isolated pointing recognition is not sufficient, as humans usually accompany their gestures with relevant natural language commands.
As ambiguities can occur both visually and textually, an interactive dialog is required to resolve a user's intentions.
In this work, we tackle this problem and present a system for interactive, multimodal, task-oriented robot dialog using pointing gesture recognition.
Specifically, we propose a pipeline constituted of state-of-the-art computer vision components to recognize objects, hands, hand orientation as well as human pose, and combine this information to identify not only pointing gesture presence but also the objects which are pointed at.
Furthermore, we provide a natural language understanding module which considers pointing information to distinguish unambiguous from ambiguous commands and responds accordingly.
Both components are integrated into the proposed interactive and multimodal dialog system.
For evaluation purposes, we introduce a challenging benchmark set for pointing recognition from human demonstration videos in unconstrained real-world scenes.
Finally, we present experimental results of both the individual components as well as the overall dialog system.

### Code

- The code of the NLU model can be found at `seq2seq-transformer`.

### Dataset

- The generated data used to train the NLU component and the test data can be found at `seq2seq-transformer/data/nlu_with_pointing`.
- To get access to the test-set videos, please fill out this [Google Form](https://docs.google.com/forms/d/1MxSr6jgmG9z2l2DDkUX071rwnNQTxgLrN24t0njtrwg).

### Models

- The NLU models can be found [here](https://www.dropbox.com/sh/vzgfznqi93x29bg/AADJjER-CqX2ZeWQ0bT7gjOea).
