[![Documentation Status](https://readthedocs.org/projects/systemrdl-compiler/badge/?version=latest)](http://systemrdl-compiler.readthedocs.io)
[![Build Status](https://travis-ci.org/SystemRDL/systemrdl-compiler.svg?branch=master)](https://travis-ci.org/SystemRDL/systemrdl-compiler)
[![Coverage Status](https://coveralls.io/repos/github/SystemRDL/systemrdl-compiler/badge.svg?branch=master)](https://coveralls.io/github/SystemRDL/systemrdl-compiler?branch=master)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/systemrdl-compiler.svg)](https://pypi.org/project/systemrdl-compiler)

# SystemRDL Compiler

The `systemrdl-compiler` module implements a generic compiler front-end for
Accellera's [SystemRDL 2.0](http://accellera.org/downloads/standards/systemrdl)
register description language. The goal of this project is to provide a free and
open compiler that lowers the barrier to entry to using an industry standard
register description language.

By providing an elaborated register model that is easy to traverse and query,
it should be far easier to write custom register space view generators.

![overview](docs/img/overview.svg)

## Documentation
See the [SystemRDL Compiler Documentation](http://systemrdl-compiler.readthedocs.io) for more details

## Install from Github using pip
mkdir path_to_folder  
cd path_to_folder  
git clone https://github.com/muneebullashariff/systemrdl-compiler.git  
cd to systemrdl-compiler  
pip install -e .  

Advantages of this approach are:  
1 - You can install package in your home projects directory.  
2 - Package includes .git dir, so it's regular Git repository. You can push to your fork right away.  

## Uninstall   
pip uninstall systemrdl-compiler  

## Related Projects
This is just the beginning! If you want to contribute, check out these other
projects.

### [PeakRDL-html](https://github.com/muneebullashariff/PeakRDL-html)
Generate dynamic register spec documentation.

### [PeakRDL-ipxact](https://github.com/SystemRDL/PeakRDL-ipxact)
Convert the SystemRDL register model to/from IP-XACT.

### [PeakRDL-uvm](https://github.com/muneebullashariff/PeakRDL-uvm)
Create a UVM Register model.

### [PeakRDL](https://github.com/SystemRDL/PeakRDL)
A command-line application that ties it all together.

## License

The SystemRDL Compiler is published and distributed under the [MIT License](LICENSE).
