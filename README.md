# DefectiveBoxIdentifier
Simple Image Analysis identifying defective box

Install first the following  necessary modules

In terminal execute the following:

which python
touch $HOME/.bash_profile
export PATH=”~/anaconda/bin:$PATH”
source $HOME/.bash_profile
conda create -n py3 python=3 anaconda
conda activate py3
source activate py3
conda update --all
conda update -n base -c defaults conda

Installing Open CV model
conda install -c https://conda.binstar.org/menpo opencv

Installing Scikitplot
conda install -c conda-forge scikit-plot 
conda install -c conda-forge/label/gcc7 scikit-plot 
conda install -c conda-forge/label/cf201901 scikit-plot
