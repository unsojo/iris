---
pretty_name: Iris Flower Measurements
license: cc0-1.0
language:
  - en
task_categories:
  - tabular-classification
source: https://archive.ics.uci.edu/dataset/53/iris
features:
  Id: int64
  SepalLengthCm: float64
  SepalWidthCm: float64
  PetalLengthCm: float64
  PetalWidthCm: float64
  Species:
    class_label: [Iris-setosa, Iris-versicolor, Iris-virginica]
---

# Iris Flower Measurements

Measurements of 150 iris flowers from three species, 50 of each. For every
flower, four sizes were measured in centimeters: the length and width of its
sepals (the green leaf-like parts under the petals) and of its petals.

It's one of the most famous datasets in statistics and machine learning. One
species (setosa) is easy to tell apart from the other two using these
measurements; the other two overlap.

> **Copy for Project Clover.** Shared here under the CC0 public-domain
> dedication it was published with. Credit belongs to R.A. Fisher and the
> UCI Machine Learning Repository.

## Files

| File | Rows |
|------|-----:|
| `data/train.csv` | 150 |

Columns:

- `Id`: row number (1–150)
- `SepalLengthCm`, `SepalWidthCm`: sepal length and width, in cm
- `PetalLengthCm`, `PetalWidthCm`: petal length and width, in cm
- `Species`: Iris-setosa, Iris-versicolor or Iris-virginica

## Known issues

Two rows (35 and 38) are known to differ slightly from Fisher's original
published numbers.

## Original source

R.A. Fisher (1936), via the UCI Machine Learning Repository:
https://archive.ics.uci.edu/dataset/53/iris

## Citation

```bibtex
@article{fisher1936iris,
  title   = {The Use of Multiple Measurements in Taxonomic Problems},
  author  = {Fisher, R. A.},
  journal = {Annals of Eugenics},
  volume  = {7},
  number  = {2},
  pages   = {179--188},
  year    = {1936}
}
```
