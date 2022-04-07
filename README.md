Graph Energy-Based Models Project
=================================

* Contains all relevant code and information for our project in the course *"CS726: Probabilistic Graphical Models"*.
* [Google Doc](https://docs.google.com/document/d/10DEu_GeTIEuG_XykWKG0XOgGVBZ9P1ROXa5RmgqPgmg/edit#heading=h.4voc5ecxzo60) (private)
* [Jamboard](https://jamboard.google.com/d/1RYFluWmmoRwnfpkHy_ivWxA7DgHoFQ-WQfqoplm9uPs/viewer?f=0) (private)
* [Random Generation Colab](https://colab.research.google.com/drive/1nYLrRYGcZ2ptkk_PLmzsu2ebqJZcIMM9) to demonstrate random generation task using Dive Into Graphs library provided by authors (their GraphEBM implementation).
* [Goal-Directed Generation Colab](https://colab.research.google.com/drive/1yUqC5qhCravn6MKyV0kTnnp-M9VrP_Br?usp=sharing) to demonstrate goal-directed generation task using our implementation of GraphEBM (for multiple features/properties). We learn the function f(y) which the authors assume to be 1 + exp(y) where y is a feature vector (QED or penalized logP). [will be made public later]
* Uses: pytorch, pytorch-geometric, dive-into-graphs.
* [TUDatasets](https://chrsmrrs.github.io/datasets/docs/datasets/) for molecules/proteins. Plans to use: QM9, BZR-MD, COX-MD, possibly PROTEINS if we can find an edge-attributed version of the dataset. Extremely ambitious: program generation. (**didn't work out**)
* [Descriptions](https://github.com/wokas36/RWK/blob/main/DATASET_DESCRIPTIONS.md) of some relevant datasets.
