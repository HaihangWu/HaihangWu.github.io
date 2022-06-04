---
excerpt: '

- - - 


## <span style="display:block;text-align:center;color:navy"> 1. Automatic problem reduction using machine learning </span>


__Motivation__: In the big data era, the size of many real-world combinatorial optimisation problems has increased significantly over the years, making the problems very hard to solve. This project aims to develop innovative problem reduction methods using machine learning to reduce the size of large-scale optimisation problems so that the reduced problems can be solved by existing optimisation algorithms. 


__Gap__: The traditional problem reduction methods are designed manually, relying on the intuition or insights of an expert. In contrast, we will develop innovative machine learning models to automate the process of problem reduction, alleviating the requirement of domain knowledge. The underlying mechanism of the proposed method is illustrated in the context of Travelling Salesman Problem (TSP) as follows. 


__Training__: Firstly, a set of small and easy TSP instances are solved to optimality, with the optimal routes highlighted in yellow in the corresponding graph (left subfigure). Features (e.g. edge weight) are then extracted to characterise each edge in the graphs, and edges are mapped to the feature space as training examples (middle subfigure). Finally, classification algorithms can be used to learn a decision boundary in the feature space to well separate edges that are part of the optimal routes from those which are not (right subfigure). 


<p align="center">
<img src="https://yuansuny.github.io/images/MLPR_training.pdf" width="900" height="180"> 
</p>


__Testing__: Given an unsolved TSP instance (left subfigure), each edge in the corresponding graph is first mapped to a point in the feature space (middle subfigure). Based on the location of the points with respect to the optimal decision boundary, the edges that are not expected to be part of the optimal route can be predicted and removed from the corresponding graph (right subfigure). 


<p align="center">
<img src="https://yuansuny.github.io/images/MLPR_testing.pdf" width="900" height="180"> 
</p>


__Current progress__: This conceptual framework was originally described in our recent IEEE TPAMI paper. As a proof of concept, we have shown that this framework works well on two problems. As this is a largely unexplored research area, we see great potential in this hybrid technique and a lot of opportunities for future work. 


__Publications__: [[IEEE TPAMI](https://yuansuny.github.io/files/Jpaper_MLPR.pdf), [OR Spectrum](https://arxiv.org/pdf/2005.05847.pdf)] 


- - - 


<br/><br/><br/>



'

---
