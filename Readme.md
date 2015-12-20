# bvu - basic vector utilities v. 01

This is a small and simple library for basic vector operation, hence the inventive name of basic vector utilities( bvu )

It implements 2d, 3d and 4d vector and matrix types, alongside with quaternions.
Most of the functions can be found in bvu_impl/funct_mat.h, bvu_impl/funct_vec.h and bvu_impl/funct_quat.h, and hopefully are pretty
self-explanatory. Besides standard inverse transpose, it also has implementations of useful [glu](https://en.wikipedia.org/wiki/OpenGL_Utility_Library) functions.

This code is in public domain. I'd appreciate contribution, but none is required.
This project has been written for educational purposes, and because I wanted to have my own library for vectors and matrices. It is
heavily inspired by [glm](http://glm.g-truc.net/0.9.7/index.html) in terms of overall api design.

The current version of the library is very far from being thoroughly tested and most likely contains many bugs.
Feel free to contact me with any comments or suggestions for improvement.

#### TODO
- eigendecomposition / svd
- PCA
- color generation ( similar to https://randomcolor.llllll.li )
