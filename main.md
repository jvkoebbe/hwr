## Homogenization Wavelet Reconstruction Method Repository

This repository contains code and manuscripts of papers that define and implement a method referred to by this author as the
Homogenization Wavelet Reconstruction (HWR) method. This work is ongoing and from time to time code and manuscripts will be
added to this repository. The content involves the use of homogenization to condition wavelet bases for elliptic partial
differential equations. The initial code has been written in Java mainly due to the fact that it is easy to get a Graphical
User Interface (GUI) up and running. The author [Joe Koebbe](http://www.math.usu.edu/~koebbe) can be contacted about the
various downloadables. However, since this is an ongoing area of work for the author, it may take some time to answer any
questions about the method.

## A Brief Introduction to the HWR method

A few years ago the author decided that it might be better to have a fast transform method for the computation of homogenized
coefficients for elliptic problems with spatially varying coefficients. After coming up with a brute force method for the
computation of a macroscopic average from microscopic values on some domain an additional discovery was made. It turns out that
the brute force transform could be rearranged so that a MultiResolution Analysis (MRA) could be defined. It turns out that the
original method of homogenization could be couched in terms of a conditioned Haar MRA. By splitting the averaging into an
arithmetic average added to a detail, the averaging formula can be split into an arithmetic average plus a detail that in turn
produces wavelet coefficients for the MRA. In addition, the analysis could be used to reconstruct the solution of the elliptic
differential equation on any scale.

More on this a bit later.... Need to add manuscripts and the latest codes I have written.....
