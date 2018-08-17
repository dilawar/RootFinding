In short, It does the same thing as GNU-gsl `gnewton` solver for finding roots
of a system of non-linear system.

The standard caveats apply when finding the multi-dimensional roots.
https://bestw.gnu.org/software/gsl/manual/html_node/Multidimensional-Root_002dFinding.html#Multidimensional-Root_002dFinding

The templated class (must be compiled with  -std=c++11). It uses boost::numeric::ublas library.

The header file contains the class, file `test_root_finding.cpp` shows how to use it.
