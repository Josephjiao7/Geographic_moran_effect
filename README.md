# Geographic Moran Effect

This repository contains the code associated with the paper:

**The Geographic Moran Effect: Theory, Methods, and Interpretation**

The study extends the classical Moran effect into a geographic context and develops a framework for identifying and interpreting synchrony induced by shared external forcing with geographically heterogeneous responses.

## Repository Structure

- `GME_simulation.ipynb`  
  Synthetic experiment used to evaluate the identification and recovery of the Geographic Moran Effect (GME) under controlled conditions.

- `Case_study_GME.ipynb`  
  Empirical application of the proposed framework to U.S. county-level presidential election data.

## Method Overview

The Geographic Moran Effect (GME) describes temporally coherent variation across geographic entities induced by a shared external forcing, while allowing the magnitude and potentially the direction of local responses to vary geographically.

The proposed framework consists of two main steps:

1. **Detection**  
   Test whether GME-type synchrony is present in the observed spatiotemporal data.

2. **Estimation and interpretation**  
   Estimate the shared temporal factor and the geographically structured sensitivity field that jointly constitute the GME.

The framework is designed to distinguish common-forcing synchrony from other forms of spatial and spatiotemporal dependence.

## Usage

The analyses can be reproduced by running the Jupyter notebooks in this repository:

```text
GME_simulation.ipynb
Case_study_GME.ipynb
```


## Citation

If you use this code or the Geographic Moran Effect framework, please cite:

> Jiao, Z., Yao, X., & Thill, J.-C. (2026). The Geographic Moran Effect: Theory, Methods, and Interpretation. *Geographical Analysis*. Forthcoming.
