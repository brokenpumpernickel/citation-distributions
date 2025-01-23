# Exploring the Dynamics of Self-Citations and Their Role in Shaping Scientific Impact


by Maciej J. Mrowinski, Aleksandra Buczek and Agata Fronczak

---

> *Understanding the mechanisms driving the distribution of scientific citations is a key challenge in assessing the scientific impact of authors. In this study, we explore the role of the preferential attachment rule (PAR) in this process. Using a data-driven approach, we analyse individual citation events from the DBLP dataset, allowing us to estimate the probability of citations being assigned preferentially. Our analysis spans both aggregated datasets and individual authors, and we explore differences between external and self-citations. Our findings reveal that, for the aggregated dataset, PAR dominates the citation distribution process, with approximately 70% of citations adhering to this mechanism. However, analysis at the individual level shows significant variability, with some authors experiencing a greater prevalence of preferential citations, particularly in the context of external citations. In contrast, self-citations exhibit notably different behaviour, with only 20% following PAR and a substantial proportion of authors showing little to no preferential self-citation. We also demonstrate that the prominence of PAR increases with an author’s citability (average citations per paper), suggesting that more citable authors are preferentially cited, while less-cited authors experience more random citation patterns. Furthermore, we show that self-citations not only may influence the distribution of external citations, but also impact bibliometric indexes such as the h-index. Our results emphasise the distinct dynamics of self-citations compared to external citations, raising questions about the mechanisms driving self-citation patterns. These findings provide new insights into citation behaviours and highlight the limitations of existing approaches in capturing the nuances of scientific impact.*

## Content

- `ranodm-par-combined.ipynb` - analysis of the combined dataset (all authors)
- `ranodm-par-individual.ipynb` - analysis of individual authors
- `ranodm-par-figures.ipynb` - scripts used to generate the figures
- `data/scopus/scopus-simulations.csv` - results of simulations based on Scopus data
- `results/` - folder with results
- `figures/` - folder with figures

## DBLP

This code requires the 12th version of the DBLP Citation Network Dataset which can be downloaded from https://www.aminer.cn/citation.

## 3DSI

We use some code from the [Three Dimensions of Scientific Impact](https://github.com/gagolews/three_dimensions_of_scientific_impact) repository accompanying the paper: 

Siudem G., Żogała-Siudem B., Cena A., Gagolewski M., Three dimensions of scientific impact, *Proceedings of the National Academy of Sciences of the United States of America (PNAS)* **117**(25), 2020, pp. 13896-13900. doi:[10.1073/pnas.2001064117](https://doi.org/10.1073/pnas.2001064117).

