# CSE 512 Final Project
####Cecilia Noecker, Alex Eng, Colin McNally, Will Gagne-Maynard

  Human-associated microbial communities, known as the human microbiome, have been associated with a range of diseases including obesity and inflammatory bowel disease. Analyses of these communities through metagenomic sequencing have focused on two related but separate questions: 1) which microbial species are present, and 2) what genetic functions are present? Our lab has developed techniques to combine the answers to these two questions--to deconvolve which genes belong to which species and thus how differences in species abundance between samples contribute to differences in function abundance. The result is a dataset of abundances of gene functions within each species for each sample. These functions can be present in all species, some subset of species, or only a single species. The high dimensional nature of these data presents challenges for visualization. A sample may have 500-1,000 different species, each with 1,000-5,000 genes (which can be grouped into a smaller set of functional categories), and a typical study consists of 10-100 samples across different environments, disease states, or time points. 

  We have developed a visualization tool to facilitate exploration of this type of dataset. Our tool can display the distributions of species abundances, the distributions of function abundances, and the contributions of each species to each function, and will furthermore allow interactive comparisons between different samples and subsets. Our preliminary plan is to implement a bipartite graph visualization showing links between taxa and genes connected to a stacked bar plot or area plot showing the composition of either genes or taxa across samples, with lots of options for interactive zooming, brushing, and sorting to explore how different subsets of taxa contribute to gene variation across samples and vice versa.


###Running Instructions
Access our visualization [HERE](http://cse512-15s.github.io/fp-cnoecker-engal-cmcn-wgagne-maynard/)

OR download this repository and run python -m SimpleHTTPServer 9000 at the root. Then access the visualization from http://localhost:9000/ using your favorite web browser.

