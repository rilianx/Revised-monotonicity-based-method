# Revised-monotonicity-based-method-for-computing-sharp-image-enclosures-of-functions

In this code, we implemente a **revised** monotonicity-based method that may be applied even if the function is non-monotonic w.r.t. its variables. The method combines basic interval-based filtering techniques with a straightforward analysis of function derivatives. 

- First, by performing filtering with partial derivatives, we detect sub-intervals in the domain where the function **certainly** increase or decrease. 
- Then, depending on the case, we can know in which subdomains in the interval should be the value maximizing (resp. minimizing) the function. 
- Finally, we use the natural interval evaluation on the subdomains maximizing $f$ (resp. minimizing $f$) for computing the upper bound (resp. lower bound) of the enclosure. We show that this method is equivalent to computing an enclosure by using the traditional monotonicity-based method when $f$ is monotonic, however, it may be much more effective when $f$ is not.

The code can be run in Google colab.
