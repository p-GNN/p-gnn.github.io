## <img src="http://latex.codecogs.com/gif.latex?p">-Laplacian Based Graph Neural Networks

### Abstract

<p align="justify">Graph neural networks (GNNs) have demonstrated superior performance for semi-supervised node classification on graphs, as a result of their ability to exploit node features and topological information. However, most GNNs implicitly assume that the labels of nodes and their neighbors in a graph are the same or consistent, which does not hold in heterophilic graphs, where the labels of linked nodes are likely to differ. Moreover, when the topology is non-informative for label prediction, ordinary GNNs may work significantly worse than simply applying multi-layer perceptrons (MLPs) on each node.</p>

<p align="justify">To tackle the above problem, we propose a new <img src="http://latex.codecogs.com/gif.latex?p\text{-Laplacian}"> based GNN model, termed as <img src="http://latex.codecogs.com/gif.latex?^p\text{GNN}">, whose message passing mechanism is derived from a discrete regularization framework and can be theoretically explained as an approximation of a polynomial graph filter defined on the spectral domain of <img src="http://latex.codecogs.com/gif.latex?p\text{-Laplacian}">. The spectral analysis shows that the new message passing mechanism works as low-high-pass filters, thus rendering <img src="http://latex.codecogs.com/gif.latex?^p\text{GNNs}"> effective on both homophilic and heterophilic graphs.</p>

<!-- <p align="justify">Empirical studies on real-world and synthetic datasets validate our findings and demonstrate that <img src="http://latex.codecogs.com/gif.latex?^p\text{GNNs}"> significantly outperform several state-of-the-art GNN architectures on heterophilic benchmarks while achieving competitive performance on homophilic benchmarks. Moreover, <img src="http://latex.codecogs.com/gif.latex?^p\text{GNNs}"> can adaptively learn aggregation weights and are robust to noisy edges.</p> -->

`Keywords`: Discrete <img src="http://latex.codecogs.com/gif.latex?p\text{-Laplacian}">, Graph Neural Networks

### Paper

Preprint: <https://arxiv.org/abs/2111.07337>

### Code

Code: <https://github.com/guoji-fu/pGNNs>

### Contact

Email: <guoji.leo.fu@gmail.com>

