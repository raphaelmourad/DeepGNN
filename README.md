# DeepGNN: Semi-supervised deep learning with graph neural network for cross-species regulatory sequence prediction


![alt text](Fig1_sketch_model.png)

# Overview
We propose a novel framework for regulatory sequence prediction using semi-supervised learning with graph neural network. For this purpose, neural networks are trained not only from labeled sequences (e.g. human genome with ChIP-seq experiment), but also from unlabeled sequences (from other species without ChIP-seq experiment, e.g. chimpanzee, rabbit or dog). In order to incorporate unlabeled sequences in the training, a graph neural network connecting homologous sequences is used. Compared to supervised learning, the proposed semi-supervized learning allows to train models from a much larger number of sequences, without needing additional experiments since many unlabeled (unannotated) genomes are already available, while the vast majority of functional experiments such as ChIP-seq are only available in human, or to some extent in mouse.

# Requirements



# Contact: 
raphael.mourad@univ-tlse3.fr
