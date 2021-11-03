
## Project Overview

We bootstrap models capable of estimating gestalt principles in sound understanding, and use them to tag and recombine continuous audio recordings to generate shorter presentations (which we call 'summaries') that result in different listening experiences.  Some contrasting examples of summaries generated from the same body of audio are given below, along with a description of the feature strategy used to generate them.  For more information about the modeling work, see:


Ishwarya Ananthabhotla, David Ramsay, Joseph Paradiso. Towards Gestalt Computation in Sound, NeurIPS Workshop on Machine Learning for Creativity and Design, 2021.


## Audio Examples

| Audio Source | Summary 1 | Summary 2 | Strategy | 
| ------------ |------------ |------------ |------------ |
| [source](https://aporee.org/maps/?loc=20205&m=roadmap) | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/jackson_most_confus.wav" type="audio/wav" /></audio> | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/jackson_least_confus.wav" type="audio/wav" /></audio> | inversely scaling confusability and memorability |
| [source](https://aporee.org/maps/?loc=33730&m=satellite) | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/saddar_most_arousal.wav" type="audio/wav" /></audio> | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/saddar_least_tot_salience.wav" type="audio/wav" /></audio> | scaling arousal and salience |
| [source](https://tidmarsh.media.mit.edu/) | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/tidmarsh_background.wav" type="audio/wav" /></audio> | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/tidmost_most_valent.wav" type="audio/wav" /></audio> | (1) semantic self-similarity; (2) high valence |
| [source](https://aporee.org/maps/?loc=13612&m=satellite) | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/dubai_least_s-ssm.wav" type="audio/wav" /></audio> | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/dubai_most_s-ssm.wav" type="audio/wav" /></audio> | scaling semantic self-similarity |
| [source](https://aporee.org/maps/?loc=18119&m=satellite) | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/mongolia_least_valence.wav" type="audio/wav" /></audio> | <audio controls="" style="width: 160px;height: 50px"><source src="./assets/audio/mongolia_most_valence.wav" type="audio/wav" /></audio> | scaling valence |