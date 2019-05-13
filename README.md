# Conda package wrapping pytest_bdd pypi package

To use -- with current working directory containing meta.yaml:

1. `conda create -n python=3 conda-build-env conda-build anaconda-client conda-verify`
2. `conda activate conda-build-env`
3. `conda-build .`
