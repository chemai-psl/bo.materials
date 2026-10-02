# Bayesian Optimization Materials

Materials collection with regards to Bayesian Optimization with links to courses, tutorials and publications. Resources related to ChemAI are listed first.

## Publications Related to BO in ChemAI

Publications related to Bayesian Optimization within ChemAI.

### Theoretical


Adresses the question of how to properly represent molecules in a BO campaign. The proposed solution uses high dimensional representations obtained from hidden spaces of neural networks and tackles corresponding challenges related to the high-dimensional nature of such representations.
```
@article{chen2026leveraging,
  title={Leveraging Chemical Hidden-Space Representations Effectively in Bayesian Optimization for Experiment Design through Dimension-Aware Hyperpriors},
  author={Chen, Guanming and Fleck, Maximilian and Stuyver, Thijs},
  journal={Journal of Chemical Theory and Computation},
  volume={22},
  number={11},
  pages={5594--5608},
  year={2026},
  publisher={ACS Publications}
}
```

Discusses different transfer learning strategies and their dependence on how molecules are represenated.
```
@article{chen2026robust,
  title={Robust transfer learning for Bayesian optimization of chemical reactions},
  author={Chen, Guanming and Parihar, Priyanka and Fleck, Maximilian and Stuyver, Thijs},
  journal={Digital Discovery},
  year={2026},
  publisher={The Royal Society of Chemistry}
}
```




### Applied


```
@article{rouffeteau2026electro,
  title={Electro-induced carbamoylation of arenes optimized by a machine learning model},
  author={Rouffeteau, Virgile and Perrier, Clara and Fleck, Maximilian and Gontard, Geoffrey and Vitale, Maxime R and Grimaud, Laurence},
  journal={Comptes Rendus. Chimie},
  volume={29},
  number={G1},
  pages={19--25},
  year={2026}
}
```


## Repositories Related to BO in ChemAI

Please check the repositories directly related to the listed publications if you find the publications interesting.


## Online Materials

Publications and materials related to Bayesian Optimization outside ChemAI.

### Publications

The canonical paper about BO in chemistry. The solution is typically referred to as EDBO.
```
@article{shields2021bayesian,
  title={Bayesian reaction optimization as a tool for chemical synthesis},
  author={Shields, Benjamin J and Stevens, Jason and Li, Jun and Parasram, Marvin and Damani, Farhan and Alvarado, Jesus I Martinez and Janey, Jacob M and Adams, Ryan P and Doyle, Abigail G},
  journal={Nature},
  volume={590},
  number={7844},
  pages={89--96},
  year={2021},
  publisher={Nature Publishing Group UK London}
}
```

Example for a BO solution coming wit a user interface. It builds on EDBO and is called EDBO+. Do not use it, we got better solutions.
```
@article{torres2022multi,
  title={A multi-objective active learning platform and web app for reaction optimization},
  author={Torres, Jose Antonio Garrido and Lau, Sii Hong and Anchuri, Pranay and Stevens, Jason M and Tabora, Jose E and Li, Jun and Borovika, Alina and Adams, Ryan P and Doyle, Abigail G},
  journal={Journal of the American Chemical Society},
  volume={144},
  number={43},
  pages={19999--20007},
  year={2022},
  publisher={ACS Publications}
}
```


### Courses and Tutorials

Lots of materials introducing BO can be found online. We recommend a quick search and finding what suits your needs best. If you find something outstanding, please report so we can share it here.

In addition we recommend the [Machine Learning in the Physical World](https://mlatcl.github.io/mlphysical/) lectures and materials. It is not specifically for chemists but the angle of view separates this one from standard BO materials and provides complementary insights and nice conceptional perspectives. The codebase of some examples is outdated so do not dig too deep. If you want to code and need a base, reach out and/or check [BayBE](https://emdgroup.github.io/baybe/stable/index.html) which runs on [botorch](https://botorch.org/) i.e. [pytorch](https://pytorch.org/).

