# MS Thesis

> I plan to update this repo frequently, but it's not complete yet.

As an additional objective in my thesis, I've decided to document and open source my work (source code and draft) in hopes that it would help others. It was a lot of work, and I'm happy if this helps someone. I'd also ask that you don't lift the thesis prose as your own.

## Planned
- [ ] a snakemake workflow for reproducibility
- [ ] MS. Biotechnology Thesis Template, Tribhuvan University (an Overleaf template would cut down time wasted on formatting)
- [ ] separate licenses for thesis and source code

## Related

[**lusc_gnn**](https://github.com/rizanB/lusc_gnn) - GCN experiment, own dataset, negative results

After listening to İsmail İlkan Ceylan and Xavier Bresson's ANAIS talk back in December, I built a PyG dataset with LUSC-relevant ppi network and tried to predict LUSC subtypes with graph-based models (GCN baseline). I dropped the idea because baseline GCN achieved 0.37 test accuracy (majority-class: 36.5%). Looking back, the graphs are definitely too sparse for message-passing to be meaningful. 

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
  note   = {dont cite this yet}
}
```

## Contributions

The work here is for my MS thesis but I'm happy to see contributions in the form of issues. If you want to contribute a PR, or would like to help, please leave suggestions in issues first.

## License
Kindly note that [this repo doesn't have a license](https://choosealicense.com/no-permission/) and that restricts being copied, distributed or modified.
