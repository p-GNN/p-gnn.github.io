## $p$-Laplacian Based Graph Neural Networks

<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

### Contents

- [Abstract](#abs)
- [Paper](#paper)
- [Code](#code)
- [Contact](#contact)


<a name="abs" />

### <details><summary>Abstract</summary><p align="justify">Graph neural networks (GNNs) have demonstrated superior performance for semi-supervised node classification on graphs, as a result of their ability to exploit node features and topological information. However, most GNNs implicitly assume that the labels of nodes and their neighbors in a graph are the same or consistent, which does not hold in heterophilic graphs, where the labels of linked nodes are likely to differ. Moreover, when the topology is non-informative for label prediction, ordinary GNNs may work significantly worse than simply applying multi-layer perceptrons (MLPs) on each node.<br>
To tackle the above problem, we propose a new $p$-Laplacian based GNN model, termed as $^p$GNN, whose message passing mechanism is derived from a discrete regularization framework and can be theoretically explained as an approximation of a polynomial graph filter defined on the spectral domain of $p$-Laplacian. The spectral analysis shows that the new message passing mechanism works as low-high-pass filters, thus rendering $^p$GNNs effective on both homophilic and heterophilic graphs.</p></details>

<!-- <p align="justify">Empirical studies on real-world and synthetic datasets validate our findings and demonstrate that $^p$GNNs significantly outperform several state-of-the-art GNN architectures on heterophilic benchmarks while achieving competitive performance on homophilic benchmarks. Moreover, $^p$GNNs can adaptively learn aggregation weights and are robust to noisy edges.</p> -->

`Keywords`: Discrete $p$-Laplacian, Graph Neural Networks

<a name="paper" />

### Paper

Preprint: <https://arxiv.org/abs/2111.07337>

<a name="code" />

### Code

Code: <https://github.com/guoji-fu/pGNNs>

<a name="contact" />

### Contact

Email: <guoji.leo.fu@gmail.com>

