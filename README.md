# Reference

Heterogeneous Graph Neural Network for Music Emotion Recognition, ISMIR 2022 [paper]
Angelo Cesar Mendes da Silva, Diego Furtado Silva and Ricardo Marcondes Marcacini

- We learn a new multimodal representation of music data composed by audio and lyrics features
- This representation is applied to a new model of music emotion classification based on a heterogeneous graph neural network
- It represents a new approach to modeling music data as a graph structure
- Our representation can be enriched with other modalities

# How to use

All notebooks are available in [notebooks](notebooks) with code to reproduce our method.
- The first step is to build a heterogeneous graph with music features. [Build heterogeneous graph](notebooks/Build_Heterogeneous_Graph.ipynb)
- In sequence, we create the GCN to classify the music emotions. [GCN](notebooks/GCN_ISMIR.ipynb).

Both notebooks can be tested directly in Google colab, [Build heterogeneous graph](https://colab.research.google.com/drive/1nskyzzNuD-ZO-pP3uUrXkjh-xIaNtZSF?usp=sharing) and [GCN](https://colab.research.google.com/drive/1n3joW7XAF9U6w49OBAEJ9zc_s1-t4_TH?usp=sharing). The supplementary files are in the folder [files](files).


# Citation 
```
@inproceedings{silva2022MRLGCN,
  title={Heterogeneous Graph Neural Network for Music Emotion Recognition},
  author={Silva, Angelo C M and Silva, Diego Furtado and Marcacini, Ricardo Marcondes},
  booktitle={Proc. of International Society for Music Information Retrieval},
  year={2022}
}
```
