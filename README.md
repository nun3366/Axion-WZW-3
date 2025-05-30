# WZW interactions of axions

## What is it?
In this work we derive all the relevant axion WZW interactions and calculate the all the relevant hadronic decay channels derived in [arxiv](url).  We make the plots of axion hadronic decay branching ratios for different parameter schemes (depending on selection).

These notebooks are based on the open-source Mathematica notebook by Maksym Ovchynnikov and Andrii Zaporozhchenko([2310.03524](https://arxiv.org/abs/2310.03524) and [2501.04525](https://arxiv.org/abs/2501.04525).)

The details are summarized in the accompanying papers [2406.11948](https://arxiv.org/abs/2406.11948) and [](https://arxiv.org/abs/).


### Dependencies

To run the notebook, two tools have to be installed: [FeynCalc](https://feyncalc.github.io/) and  [xAct_xTerior](https://github.com/xAct-contrib/xTerior) 

### Code structure

The main notebook is "main.nb"  The code is modular, with various modules located in the folder `notebooks`.  Besides the mass of axion/ALP m\_a and decay constant f\_a, we have seven more parameters that are axion coupling to gluons $ c_{gg}$ and to left/right-handed u/d/s flavor quarks $ c_{L/R}^{u/d/s}$.  The major innovations of our work is contained in the "WZW\_axion\_interactions.nb" which includes all the details of auxiliary parameter independent calculations of WZW interactions of axions.


