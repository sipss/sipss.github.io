# SIPSS <img src='android-chrome-192x192.png' align="right" height="139" />

[![Github.io](https://img.shields.io/static/v1?label=Github&message=Page&color=yellow)](https://sipss.github.io/)
[![Linkedin](https://img.shields.io/static/v1?label=Linkedin&message=Profile&color=darkblue)](https://www.linkedin.com/in/santiago-marco-ibec-ub/)
[![IBEC](https://img.shields.io/static/v1?label=IBEC&message=Page&color=lightgreen)](https://ibecbarcelona.eu/sensingsys)
[![UB](https://img.shields.io/static/v1?label=UB&message=Page&color=orange)](https://www.ub.edu/portal/web/dp-electronics/research-groups1)
[![Publications](https://img.shields.io/static/v1?label=Scholar&message=Publications&color=blue)](https://scholar.google.es/citations?user=ql79H9cAAAAJ&hl=es&oi=ao)

The Signal and Information Processing for Sensing Systems group develops algorithmic solutions for the automatic processing of Gas Sensor Array, Gas Chromatography – Ion Mobility Spectrometry (IMS), Nuclear Magnetic Resonance (H-NMR), and Mass Spectrometry (GC/LC-MS, MSI) data for metabolomics, food, and environmental samples.

In this context, we are interested in intelligent chemical instruments for the detection of gases, volatile compounds, and smells. These systems can be based on an array of nonspecific chemical sensors with a pattern recognition engine, taking inspiration from the olfactory system. Some spectrometries, e.g. Ion Mobility Spectrometry, are capable of very fast analysis with good detection limits but poor selectivity. These technologies have been proposed for the fast determination of the volatolome (volatile fraction of the metabolome), instead of the reference technique of gas chromatography – mass spectrometry.


## About AlpsNMR package

Checkout the [AlpsNMR](https://sipss.github.io/AlpsNMR/index.html) documentation website that shows how to import data and preprocess it using AlpsNMR. See our [publication](https://doi.org/10.1093/bioinformatics/btaa022) and the [Bioconductor page](https://www.bioconductor.org/packages/release/bioc/html/AlpsNMR.html) for further details.


```r
if (!"BiocManager" %in% rownames(installed.packages()))  
    install.packages("BiocManager")  
BiocManager::install("AlpsNMR")
```


