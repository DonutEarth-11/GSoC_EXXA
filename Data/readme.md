<h1 align="center">
Dataset Generation</br>
</h1>

This folder contains the notebooks used for testing POSEIDON package, generating the dataset, removing unphysical data and running Nested sampling retrieval.

We used POSEIDON to generate the forward models, which is a Python-based package that can be used to generate a model planet spectrum for a given set of parameters, such as the parameters of the star-planet system and the atmospheric properties.


## Notebooks
* [Testing using WASP39b H2O forward model](Data\transmission_poseidon_h20.ipynb)
* [Generating, binning and saving 100k models](Data\transmission_poseidon_r1000_data_100k.ipynb)
* [Unphysical forward models](Data\100k_dataset_nan.ipynb)
* [Nested Sampling Retrieval](Data\pos_100k_ret.ipynb)
* [Cornerplot from retrieval](Data\corner.pdf)
