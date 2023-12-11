# Code and datasets for C.elegans connectome analysis

This is a connected open-source repository for the publication "Communities in C.elegans connectome through the prism of non-backtracking walks" published in Scientific Reports (2023).
The reference will be provided soon.

Authors: Arsenii Onuchin, Alina Chernizova, Mikhail Lebedev, Kirill Polovnikov

Abstract:
The fundamental relationship between the mesoscopic structure of neuronal circuits and organismic functions they subserve is one of the major challenges in contemporary neuroscience. Formation
of structurally connected modules of neurons enacts the conversion from single-cell firing to largescale behaviour of an organism, highlighting the importance of their accurate profiling in the data.
While connectomes are typically characterized by significant sparsity of neuronal connections, recent advances in network theory and machine learning have revealed fundamental limitations of traditionally used community detection approaches in cases where the network is sparse. Here we
studied the optimal community structure in the structural connectome of Caenorhabditis elegans, for which we exploited a non-conventional approach that is based on non-backtracking random walks,
virtually eliminating the sparsity issue. In full agreement with the previous asymptotic results, we demonstrated that non-backtracking walks resolve the ground truth annotation into clusters on
stochastic block models (SBM) with the size and density of the connectome better than the spectral methods related to simple random walks. Based on the cluster detectability threshold, we determined
that the optimal number of modules in a recently mapped connectome of C. elegans is 10, which precisely corresponds to the number of isolated eigenvalues in the spectrum of the non-backtracking
flow matrix. The discovered communities have a clear interpretation in terms of their functional role, which allows one to discern three structural compartments in the worm: the Worm Brain (WB), the
Worm Movement Controller (WMC), and the Worm Information Flow Connector (WIFC). Broadly, our work provides a robust network-based framework to reveal mesoscopic structures in sparse
connectomic datasets, paving way to further investigation of connectome mechanisms for different functions.

![Connectome in the nutshell](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOGo0NGptazNrZzU2bWppOWF0bjEzamdwNDdld2tsYjlpdTllb29scCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JLi9sfhKeZ3LCZygti/giphy-downsized-large.gif)

Contact: 
Kirill Polovnikov
kipolovnikov@gmail.com
