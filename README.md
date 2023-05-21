# Mining Complex Networks - Practical Methods for Mining Graphs using Python-igraph

**Part 1: EDA**

- 1.1 Relational data as graphs
    - basic igraph commands, main dataset, types of graphs
- 1.2 Exploratory data analysis (EDA)
    - degree, paths, connected components
- 1.3 Node importance: 
    - coreness, centrality, betweenness

**Part 2: Clustering**

- 2.1 Transitivity
    - triangles and other motifs, local and global clustering coefficients, cliques
- 2.2 Clustering: modularity, Louvain, Leiden, ECG and properties; other methods
    - illustrations on various graphs; measures of cluster quality; ego-nets vs clusters
- 2.3 Random graph models and benchmarks (ex: Erdos-Renyi, ABCD)
    
## Reference Book

* "Mining Complex Networks" (https://www.torontomu.ca/mining-complex-networks) by B. Kaminski, P. Pralat and F. Théberge.

* Further notebooks and datasets to accompany this textbook can be found at: https://github.com/ftheberge/GraphMiningNotebooks

## igraph references

* python-igraph documentation: https://igraph.readthedocs.io/en/0.10.2/

* Introductory guide: https://towardsdatascience.com/newbies-guide-to-python-igraph-4e51689c35b4


## Software environment

The Python Notebook was created under the following conda environment:

```
conda create --name mining_complex_networks python=3.10 numpy pandas jupyter matplotlib pycairo scikit-learn
source activate mining_graphs
pip install igraph
pip install partition-igraph
pip install gravis

```

