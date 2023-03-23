# Object counting by segmentation ML-INFN

[![GitHub commit](https://img.shields.io/github/last-commit/clissa/object-counting-ML-INFN)](https://github.com/clissa/object-counting-ML-INFN)

---

![cover](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-021-01929-5/MediaObjects/41598_2021_1929_Fig1_HTML.jpg?as=webp)
`Image from original paper` [Automating cell counting in fluorescent microscopy through deep learning with c-ResUnet](https://rdcu.be/c8hKy)

 Counting objects is a learning task common to many applications, from video sourveillance to agriculture 4.0, not to mention studies in life-sciences and medicine. However, this task is typically performed manually by domain experts, becoming very demanding in terms of time and human resources. Also, this increases the chances of errors due to distraction or fatigue.

This use-case deals with an approach to automate recognition and counting of objects in images.
Specifically, we frame the problem as a *semantic segmentation* task and we use the [c-Resunet](https://rdcu.be/c8hKy) network architecture, taking the [Fluorescent Neuronal Cells dataset](http://amsacta.unibo.it/6706/) as a benchmark.

![architecture](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-021-01929-5/MediaObjects/41598_2021_1929_Fig2_HTML.png?as=webp)
`Image from original paper` [Automating cell counting in fluorescent microscopy through deep learning with c-ResUnet](https://rdcu.be/c8hKy)

The material is organized into notebooks that cover every stage of a realistic data analysis pipeline. In particular, a great deal of attention is devoted to EDA both to expose the challenges of the dataset and to evaluate the results. Likewise, technical aspects of the fastai implementation are detailed. 
For more details on the implementations see `blocks.py` and `utils.py` scripts.


## Installation

```
git clone git@github.com:clissa/object-counting-ML-INFN.git
```

After cloning the repository, simply follow the instructions in `installation.txt` to set up your workspace. Then download the data as described in the notebook `01. Exploratory Data Analysis.ipynb`. Each step of the analysis is detailed in a dedicated notebook under the folder `notebooks/`.


## References
Morelli, R., Clissa, L., Amici, R. et al. [Automating cell counting in fluorescent microscopy through deep learning with c-ResUnet.](https://rdcu.be/c8hKy) Sci Rep 11, 22920 (2021).

Clissa, L. [Supporting Scientific Research Through Machine and Deep Learning: Fluorescence Microscopy and Operational Intelligence Use Cases.](http://amsdottorato.unibo.it/10016/) PhD Thesis (2022)

Clissa, L. et al. [Fluorescent Neuronal Cells.](http://amsacta.unibo.it/6706/) AMS Acta (2021)

[Fluorescent Neuronal Cells dataset – part I](https://medium.com/towards-data-science/fluorescent-neuronal-cells-dataset-part-i-ac123196b963), TDS Blog

[Fluorescent Neuronal Cells dataset – part II](https://medium.com/towards-data-science/fluorescent-neuronal-cells-dataset-part-ii-e1ac27e26d7), TDS Blog

[Fluorescent Neuronal Cells dataset – part III](https://medium.com/towards-data-science/fluorescent-neuronal-cells-dataset-part-iii-287c2a4f1a22), TDS Blog