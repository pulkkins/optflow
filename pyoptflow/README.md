Overview
--------

Pyoptflow is a Python interface for the Optflow C++ library. Currently the 
interface covers the motion extraction algorithms. In addition, pyoptflow 
implements methods for motion-based interpolation and extrapolation and 
visualization of motion fields.

Dependencies and installation
-----------------------------

Required dependencies:

  Package       | Version   | Website
  ------------- | --------- | --------------------
  Python        | == 2.7    |
  Boost.Python  | >= 1.50   | http://www.boost.org
  numpy         | >= 1.8    | http://www.numpy.org
  scipy         | >= 0.13   | http://www.scipy.org
  matplotlib    | >= 1.3    | http://matplotlib.org

Optional dependencies:

  Package       | Version   | Website
  ------------- | --------- | ---------------------
  h5py          | >= 2.2    | http://www.h5py.org

External algorithms that can be optionally compiled/linked with pyoptflow:

  Algorithm                | Website
  -------------------------|-----------------------------------------------------
  Brox (original version)  | https://lmb.informatik.uni-freiburg.de/research/opticalflow
  Brox (IPOL version)      | http://www.ipol.im/pub/art/2013/21
  CLG                      | http://www.ipol.im/pub/art/2015/44

To install pyoptflow, install the Optflow C++ package first, extract the 
pyoptflow tarball and then type the following command in the pyoptflow directory:

    sudo python setup.py install

The default installation directory for the pyoptflow modules is `/usr/local`. 
An alternative installation directory can be specified by the `--prefix` option.

Author: Seppo Pulkkinen <seppo.pulkkinen@fmi.fi>
