---
jupyter:
  jupytext:
    formats: ipynb,md
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.14.4
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region -->
[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# The Hot Spot Coverage Patrol Problem: Formulations and Solution Approaches

This archive is distributed in association with the [INFORMS Journal on Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The purpose of this repository is to share the data used in the paper [The Hot Spot Coverage Patrol Problem: Formulations and Solution Approaches] by Y. Luo, B. Golden, and R. Zhang.

### Cite
Below is the BibTex for citing this version of the data.

```bib
@article{hscpp_data,
    title = {Data for The Hot Spot Coverage Patrol Problem: Formulations and Solution Approaches},
    author = {Y. Luo, B. Golden, and R. Zhang},
    year = {2023},
    journal = {INFORMS Journal on Computing},
    note = {Forthcoming},
    url = {https://github.com/INFORMSJoC/2022.0192},
}
```

## Instances

Instances contained in folder `data`. Both real-world and simulated instances are provided here. To use the data, install the package pickle by

```bash
pip install pickle
```
and use the following command:

```bash
with open("filename", "rb") as fp: 
    [Prize, dist_matrix, coordinates] = pickle.load(fp)
```

Each file includes the prize, the distance matrix, and the coordinates of the nodes.


## Algorithm
The algorithms in this paper will be provided at a later date when there is no conflict of interest.

## Results
We report the figures of our paper in the Folder `results`

## License

This software is released under the MIT license, which we report in file `LICENSE`.
<!-- #endregion -->

```python

```
