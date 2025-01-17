[![Test-WecOptTool](https://github.com/SNL-WaterPower/WecOptTool/actions/workflows/build-test-doc.yml/badge.svg)](https://github.com/SNL-WaterPower/WecOptTool/actions/workflows/python-package.yml)
[![Coverage Status](https://coveralls.io/repos/github/SNL-WaterPower/WecOptTool/badge.svg?branch=main)](https://coveralls.io/github/SNL-WaterPower/WecOptTool?branch=main)

# WecOptTool
The Wave Energy Converter Design Optimization Toolbox (WecOptTool) allows users to perform wave energy converter (WEC) device design optimization studies with constrained optimal control.

**NOTE:** If you are looking for the WecOptTool code used in previous published work (MATLAB version) please see [WecOptTool-MATLAB](https://github.com/SNL-WaterPower/WecOptTool-MATLAB).

## Project Information
Refer to [WecOptTool documentation](https://snl-waterpower.github.io/WecOptTool/) for more information, including project overview, tutorials, theory, and API documentation.

## Getting started
WecOptTool requires Python 3.9 or 3.10.

**Option 1** - using `Conda` for [Capytaine](https://github.com/mancellin/capytaine) (requires the [Conda package manager](https://docs.conda.io/en/latest/)):

```bash
conda install -c conda-forge capytaine
pip install wecopttool
pip install wavespectra
```

**Option 2** - using `pip` for [Capytaine](https://github.com/mancellin/capytaine) (requires Fortran compilers):

```bash
pip install wecopttool
pip install wavespectra
```

## Tutorials
The tutorials can be found in the `examples` directory and are written as [Jupyter Notebooks](https://jupyter.org/).
To run the tutorials, first download the notebook files and then, from the directory containing the notebooks, run `jupyter notebook`.
Using `git` to obtain the notebooks this can be done by running

```bash
git clone https://github.com/SNL-WaterPower/WecOptTool.git
cd WecOptTool/examples
jupyter notebook
```

## Getting help
To report bugs, use WecOptTool's [issues page](https://github.com/SNL-WaterPower/WecOptTool/issues).
For general discussion, use WecOptTool's [discussion page](https://github.com/SNL-WaterPower/WecOptTool/discussions)

## Contributing
If your interersted in contributing to WecOptTool see our [contribution guidelines](https://github.com/SNL-WaterPower/WecOptTool/blob/main/.github/CONTRIBUTING.md).
