# polychrom-hoomd

[**HOOMD-blue**](https://hoomd-blue.readthedocs.io/en/v3.11.0/)-based package for coarse-grained polymer and chromosome simulations.

## Installation 

You may use the provided `environment.yml` file to create a conda environment `polychrom-hoomd` including all required software packages:

~~~shell
conda env create -f environment.yml
conda activate polychrom-hoomd
~~~

Note that this environment should be built on a node with GPU access (and CUDA). HOOMD may silently default to CPU version if this is not the case. 

Following which the code may be installed as usual,
~~~shell
python3 -m pip install -e .
~~~

## Usage

See the attached Jupyter notebook tutorials within the `examples` directory.
