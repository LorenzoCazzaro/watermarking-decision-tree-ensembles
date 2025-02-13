# Watermarking Decision Tree Ensembles

This repository contains the implementation of the watermarking algorithm for decision tree ensembles (Random Forests) proposed by Calzavara et. al. in their research paper titled _Watermarking Decision Tree Ensembles_ accepted at the [28th International Conference on Extending Database Technology](https://edbticdt2025.upc.edu//). This repository also contains the code and the scripts to reproduce the experiments described in the paper.

## Artifact organization

The artifact is organized in the following folders:

- the *datasets* folder contains the data used to train the models and the models used in the experiments in the joblib format.
- the *src* folder contains the python notebooks containing the scripts to run the watermarking algorithm on the three datasets presented in the paper. Moreover, the notebooks contain also the code to reproduce the results presented in the paper;
- the *results* folder contains a zip folder containing the figures shown in the paper and the intermediate data produced to generate the figures.

## Download the repo

Download the repo using `git clone <repo_link>`.

## System configuration

Here we report some details about the software. Our system used:
<ul>
	<li> python (3.10) </li>
	<li> some python modules: scikit-learn (1.0.2), numpy (1.26.4), pandas (2.2.1), matplotlib (3.5.1).
	<li> z3-solver==4.13.0.0 </li>
</ul>

## Usage of the tool and reproduce the experiments

At the moment, the implementation of the watermarking algorithm and the other code to reproduce the experiments are inside python notebooks. Precise instructions on how to use the algorithm and reproduce the experiments using independent python scripts will be available after refactoring the code in separate python scripts. Available soon...

## Credits

The Bibtex entry to cite the paper will be available after the publication of the camera-ready version of the paper. 

Thanks to [Donald Gera](https://github.com/Donaldxx) for contributing to the project and preparing the first version of the notebooks.

## Support 

If you want to ask questions about the artifact and notify bugs, feel free to contact us by sending an email to lorenzo.cazzaro@unive.it.