# seqwalk paper reproducibility

This repository contains the code necessary to reproduce results from the paper. For the seqwalk software library, see [here](https://github.com/ggdna/seqwalk).

## Some potentially helpful tips

- `DeLOB_benchmarks.ipynb` contains the code for our reimplementation of DeLOB, and our benchmarking presented in Figure 2.

- Supplementary notes 4-6 contain analyses of many SeqWalk generated libraries. Rather than including all 11 million sequences in the repository, we instead include `library_generation.ipynb`, which is a self-contained notebook that will generate all necessary libraries, which can then be analysed by `gc_content.ipynb, melting_temp.ipynb, secondary_struct.ipynb` 