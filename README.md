# Navon dataset from "The Origins and Prevalence of Texture Bias in Convolutional Neural Networks"
	
This repository contains the Navon dataset used in the paper ["The Origins and Prevalence of Texture Bias in Convolutional Neural Networks"](https://arxiv.org/abs/1911.09071) by Katherine Hermann, Ting Chen, and Simon Kornblith. 
	
Introduced by psychologist David Navon in the 1970s to study how people process global versus local visual information (Navon 1977), Navon figures consist of a large letter ("shape") rendered in small copies of another letter ("texture"). We rendered each possible shape-texture combination (26 x 26 letters) at 5 positions. Each image was rotated with an angle drawn from [-45, 45] degrees. In our experiments, we excluded images with matching shape and texture, though we include them here.
	
`navon_rotated_stims` contains subdirectories corresponding to shape labels, each containing images of that shape.
	
`generate_navon_stims.py` is the script used to generate the stimuli.
