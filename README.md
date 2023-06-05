# Bounds-on-Leray-Numbers

This project is started to support the computations on our paper "Weak Eisenbud-Goto conjecture for Stanley-Reisner ideal" joint work with Jinha Kim, Minki Kim, and Yeongrak Kim.

If you need some assistance to install the computer software system "Macaulay2", see the webpage http://macaulay2.com/ and follow their instructions.

This project contains some codes on Macaulay2 of functions that gives a upper bounds on Leray numbers of the simplicial complex.
To use the codes, please download the file "LerayBounds.m2", put the file in "codes" folder of your Macaulay2 directory, and use the command 'load "LerayBounds.m2"' in Macaulay2. 

We currently provide the following codes for upper bounds on Leray number of the simplicial complexes in "LerayBounds.m2".
- "strBoundwOrder (List)" provides the value $M$ in the paper for an upper bound on Leray numbers of a simplicial complex given the linear order of facets (in the list).
- "strBound (SimplicialComplex)" provides the value $M$ for an upper bound on Leray numbers of a simplicial complex.
- "strBoundFacets (SimplicialComplex)" provides the lists of facet orderings such that the bounds on Leray number with respect to the facet ordering is same as the bounds of the complex.
- "connBoundwOrder (List)" provides the value $N$ in the paper for an upper bound on Leray numbers of a simplicial complex given the linear order of facets (in the list).
- "connBound (SimplicialComplex)" provides the value $N$ for an upper bound on Leray numbers of a simplicial complex.
- "connBoundFacets (SimplicialComplex)" provides the lists of facet orderings such that the bounds on Leray number with respect to the facet ordering is same as the bounds of the complex.
- "weakShellwOrder (List)" provides a Boolean value: the output is true if it is a weak shelling of the complex and false if it is not a weak shelling of the complex.
- "weakShelling (SimplicialComplex)" provides a weak shelling of the complex. If it is not weak shellable, the empty list is printed.
- "isWeakShellable (SimplicialComplex)" provides a boolean value: "true" is printed if it is weak shellable and "false" is printed if is not weak shellable.
- "weakShellFacets (SimplicialComplex)" provides the list of facet orderings that are weak shelling of the complex.
- "minOrder (SimplicialComplex)" provides a facet order so that the facets are maximally intersected for each steps in adding facets along the facet order.

In "examples.m2", we provide some examples that we have tested.

