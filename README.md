# Adaptation Algorithms for Neural Network-Based Speech Recognition: An Overview

 Data and scripts used to produce meta-analysis results in our review paper on adaptation algorithms for speech recognition ([IEEE link](https://ieeexplore.ieee.org/document/9296327), [Arxiv link](https://arxiv.org/pdf/2008.06580.pdf)), published in [IEEE Open Journal of Signal Processing](https://signalprocessingsociety.org/publications-resources/ieee-open-journal-signal-processing/about-open-journal-signal-processing).

## Data

The raw meta-analysis data is in the `data/ojsp-meta.csv` file. It is used in `analysis.ipynb` noteboook to produce aggregated results in (mostly) tabular form (for now). For the paper we directly generated latex plots using `pdfplots` package. If for some reason you need to regenerate them, raw sources are produced by the notebook and can be found in `/content/figs` Colab directory. Note that some of these were manually modified directly in the paper for better visuals (and their Latex sources can be found on Arxiv). 

## Citations

If you find the paper useful, please consider citing it as:

```
@ARTICLE{9296327,
  author={P. {Bell} and J. {Fainberg} and O. {Klejch} and J. {Li} and S. {Renals} and P. {Swietojanski}},
  journal={IEEE Open Journal of Signal Processing}, 
  title={Adaptation Algorithms for Neural Network-Based Speech Recognition: An Overview}, 
  year={2021},
  volume={2},
  number={},
  pages={33-66},
  doi={10.1109/OJSP.2020.3045349}}
```

