# Potentially hard graphs for multilevel graph partitioning solvers
Benchmark from the paper
Safro, Ilya, Peter Sanders, and Christian Schulz. "Advanced coarsening schemes for graph partitioning." Journal of Experimental Algorithmics (JEA) 19 (2015): 1-24.

Graph partitioning is a class of problems used in many fields of computer science and engineering. Applications include VLSI design, load balancing for parallel computations, machine learning to mention just a few. The multilevel graph partitioning solvers are among the most successful practical approaches. In this benchmark we include potentially hard graphs for multilevel and other graph partitioners. 

Highlights of technical details: 										
These graphs have been created from the real-life graphs by adding new edges (less than 3%) 						
Experimental settings (see our paper): imbalance = 3%, k=2,4,8 								
For multilevel algorithms designers: some of these graphs are here because of the big gap between the final result and that before the last refinement. 

If you use this benchmark, please cite us
@article{safro2015advanced,
  title={Advanced coarsening schemes for graph partitioning},
  author={Safro, Ilya and Sanders, Peter and Schulz, Christian},
  journal={Journal of Experimental Algorithmics (JEA)},
  volume={19},
  pages={1--24},
  year={2015},
  publisher={ACM New York, NY, USA}
}
