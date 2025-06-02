# WZW Interactions of Axions

## What is it?
In this work, we implement the routines to derive the relevant axion WZW interactions with the ground-state (axial-)vector mesons and electroweak gauge bosons and calculate the relevant hadronic decay widths derived in [2406.11948](https://arxiv.org/abs/2406.11948) and [2505.24822](https://arxiv.org/abs/2505.24822).  We also provide the routines to plot the hadronic axion decay widths under different parameter schemes of the user's choice.

These notebooks are based on the open-source Mathematica notebooks written by Maksym Ovchynnikov and Andrii Zaporozhchenko introduced in [2310.03524](https://arxiv.org/abs/2310.03524) and [2501.04525](https://arxiv.org/abs/2501.04525).

### Dependencies

To run the routines, one must first install [FeynCalc](https://feyncalc.github.io/) and [xAct-xTerior](https://github.com/xAct-contrib/xTerior).

### Repository structure

The main routines are implemented in `main.nb`, with the basis modules defined in the notebooks stored in the folder `notebooks`. In addition to the axion/ALP mass $m_a$ and axion decay constant $f_a$, the user should specify seven other parameters: the axion couplings to gluons $c_{gg}$ and left/right-handed u/d/s-quarks $c_{L/R}^{u/d/s}$. The major contribution of this work, the details of auxiliary parameter cancellation in the effective axion WZW couplings, is implemented in `WZW_axion_interactions.nb`.
