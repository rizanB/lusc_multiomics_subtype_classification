# (working title) Comparative Multi-Omics Classification of LUSC Molecular Subtypes Using Interpretable Machine Learning

> I plan to update this repo frequently, but it's not complete yet.

As an additional objective in my thesis, I've decided to open source my work (source code and draft, and a proper LaTex template since that's not a standard practice for MS theses in Biotechnology, at least not at my institution) in hopes that it would help others. It was a lot of work, and I'm happy if this helps someone. I'd also ask that you don't lift the thesis prose as your own.

## Data availability

This repository does not host any TCGA data. All data was obtained from public sources and can be
re-downloaded using the instructions in [`data/README.md`](data/README.md):

- **Gene expression, methylation, miRNA, CNV, RPPA:** [UCSC Xena Browser](https://xenabrowser.net/), TCGA-LUSC cohort
- **Somatic mutation (MAF):** [TCGAbiolinks](https://bioconductor.org/packages/TCGAbiolinks/), TCGA-LUSC

## Citation

If you use this code, please cite:

```bibtex
@mastersthesis{bhandari2026lusc,
  title  = {Comparative Multi-Omics Classification of Lung Squamous Cell Carcinoma
            Molecular Subtypes Using Interpretable Machine Learning},
  author = {Bhandari, Acchyut},
  school = {Central Department of Biotechnology, Tribhuvan University},
  address  = {Kathmandu, Nepal},
  year   = {2026},
  note   = {will get a doi issued once I'm happy with the final draft}
}
```

## Contributions

The work here is for my MS thesis but I'm happy to see contributions in the form of issues. If you want to contribute a PR, please leave suggestions in issues first.

## License
Kindly note that [this repo doesn't have a license](https://choosealicense.com/no-permission/) and that restricts being copied, distributed or modified.
