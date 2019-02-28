# GDL
Code(matlab version and C++ version) for paper "Graph Regularized Dual Lasso for Robust eQTL Mapping"(ISMB'14)


Ref:
Graph Regularized Dual Lasso for Robust eQTL Mapping. 
Wei Cheng, Xiang Zhang, Zhishan Guo, Yu Shi and Wei Wang.
In Proceedings of the 22nd Annual International Conference on Intelligent Systems for Molecular Biology (ISMB'14) , 2014


For the matlab version of proposed G-Lasso, GD-Lasso, and GGD-Lasso.
Please refer simulation.m for the use of those methods.
GGD-Lasso needs extra snp location information "yeast_SNP_location.txt" and PPI information.

For the C++ version of GGD-Lasso, GD-Lasso, and G-Lasso.
please use:
 gmake -f nm_gnu.mak

to compile the tools.
