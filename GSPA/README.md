# GSPA

These are the code I've used to generate the figures for my lab meeting presentation.

```bibtex
@article{GSPA,
   author = {Venkat, Aarthi and Leone, Sam and Youlten, Scott E. and Fagerberg, Eric and Attanasio, John and Joshi, Nikhil S. and Perlmutter, Michael and Krishnaswamy, Smita},
   title = {Mapping the gene space at single-cell resolution with gene signal pattern analysis},
   journal = {Nature Computational Science},
   volume = {4},
   number = {12},
   pages = {955-977},
   abstract = {In single-cell sequencing analysis, several computational methods have been developed to map the cellular state space, but little has been done to map or create embeddings of the gene space. Here we formulate the gene embedding problem, design tasks with simulated single-cell data to evaluate representations, and establish ten relevant baselines. We then present a graph signal processing approach, called gene signal pattern analysis (GSPA), that learns rich gene representations from single-cell data using a dictionary of diffusion wavelets on the cell–cell graph. GSPA enables characterization of genes based on their patterning and localization on the cellular manifold. We motivate and demonstrate the efficacy of GSPA as a framework for diverse biological tasks, such as capturing gene co-expression modules, condition-specific enrichment and perturbation-specific gene–gene interactions. Then we showcase the broad utility of gene representations derived from GSPA, including for cell–cell communication (GSPA-LR), spatial transcriptomics (GSPA-multimodal) and patient response (GSPA-Pt) analysis.},
   ISSN = {2662-8457},
   DOI = {10.1038/s43588-024-00734-0},
   url = {https://doi.org/10.1038/s43588-024-00734-0},
   year = {2024},
   type = {Journal Article}
}
```

## Requirements

I run the following python on jupyter notebook.

```text
python==3.12.9
jupyter_core==5.7.2
jupyter_client==8.6.3
ipython==8.31.0
ipykernel==6.29.5
```

And the following packages are required:

```text
numpy==1.26.4
pandas==2.2.3
matplotlib==3.10.0
seaborn==0.13.2
networkx==3.4.2
manim==0.18.1
```

You would also need a valid LaTeX installation to run the manim code.
I used [TexLive](https://www.tug.org/texlive/quickinstall.html) 2025.01.06.

## Usage

Enjoy!
