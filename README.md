# graph-kernel
   
[**KeLP**][kelp-site]  is the Kernel-based Learning Platform developed in the [Semantic Analytics Group][sag-site] of the [University of Roma Tor Vergata][uniroma2-site] and the Qatar Computing Research Institute [QCRI][qcri-site].

This is the **KeLP** graph-kernel module and it contains some state-of-the-art kernels for graphs.

Currently the following kernels are implemented:

* _ShortestPathKernel_: it is the implementation of the shortest path kernel described in (Borgwardt '05)

* _WLSubtreeMapper_: it is actually a manipulator that extracts a _SparseVector_ from a given graphs. Such _SparseVector_ corresponds to the explicit feature space projection of the WLSubtree Kernel for graphs (Shervashidze '11). The features correspond to the trees resulting from breadth-first visits of depth up to _h_. The manipulator enrich an Example with these vectorial representation allowing to exploit them with kernel methods or with linear learning algorithms. 


============
REFERENCES:

(Borgwardt '06) K. M. Borgwardt and H. P. Kriegel, _Shortest-Path Kernels on Graphs_, in Proceedings of the Fifth IEEE International Conference on Data Mining, 2005, pp. 74–81.

(Shervashidze '11) N. Shervashidze, P. Schweitzer, E. J. van Leeuwen, K. Mehlhorn and K. M. Borgwardt _Weisfeiler-lehman graph kernels_, JMLR, vol. 12, pp. 2539–2561, 2011



[sag-site]: http://sag.art.uniroma2.it "SAG site"
[uniroma2-site]: http://www.uniroma2.it "University of Roma Tor Vergata"
[qcri-site]: http://www.qcri.org.qa/ "QCRI"
[kelp-site]: http://sag.art.uniroma2.it/demo-software/kelp/ "KeLP website"
