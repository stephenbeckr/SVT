# SVT
Singular Value Thresholding "SVT" (legacy code)

This is taken from the SVT website [svt.stanford.edu](http://svt.stanford.edu); please refer to that website for information on what SVT is used for. This repository contains MATLAB code, along with C/mex code, so it must be installed with a compiler.

Specifically, these files were taken from the most recent package there, [svt.stanford.edu/code/SVT_2011-04-25.zip](http://svt.stanford.edu/code/SVT_2011-04-25.zip), and were updated starting in June 2019 to be compatible with recent OS and Matlab versions.

This package is not *actively* maintained, and SVT is not always the best state-of-the-art algorithm, but we'll do our best to give partial support.

Original code written for SVT by Emmanuel Candès and Stephen Becker, in addition to code for PROPACK. This variant of PROPACK has been re-used in many other matrix completion codes.

Maintained by Stephen Becker (email: firstname.lastname @ colorado.edu )

# Compiling instructions
Download the entire repository, then go to the `SVD_utilities` subdirectory and run `install_mex.m` from within MATLAB.  Test this with `test_MEX.m` and `test_PROPACK.m`.  Then go back to the parent directory and run `Test_SVT.m`

Note: we have included precompiled binaries for several architectures; you may want to try these before running `insteall_mex.m` in case they work out-of-the-box for you
