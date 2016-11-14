# How-to-install-numba

To run some of the tracking codes, like https://github.com/abewley/sort, you would require python-numba. 

The following are the dependencies for Numba:
1. llvmlite
2. Numpy
3. SciPy

# Installing llvmlite

llvmlite requires at least llvm-3.7 or more. 
First install llvm by the following command:

    $ sudo apt-get install llvm-3.8

clone the llvm repo into your local type:

    $ git clone https://github.com/numba/llvmlite
    $ cd llvmlite
    $ sudo LLVM_CONFIG=/usr/bin/llvm-config-3.8 python setup.py install
    
# Install numba

    $ sudo pip install numba
