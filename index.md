---
title: Scalable algorithms in applicable mathematics
---

This is the page of **Math 692 Graduate Seminar: Scalable algorithms in applicable mathematics** in Spring 2023, in the [Dept. of Mathematics and Statistics](http://www.uaf.edu/dms/) at the [University of Alaska Fairbanks](http://www.uaf.edu/).

[Jump to schedule of talks at bottom.](#schedule)

### official details

Organizer: [Ed Bueler](http://bueler.github.io/), [elbueler@alaska.edu](mailto:elbueler@alaska.edu).

Time and place: Thursdays 4-5pm, Chapman 104

Credits: 1.0, but **non-credit attendance is also strongly encouraged**.  (CRN 37822 for in-person section 901, 37821 for synchronous zoom section 701.)  If you want to take the seminar for credit then you should expect to give a least one presentation.

## proposed content

My idea is to have a seminar where we can learn about mathematical (or somewhat mathematical) algorithms which are aimed at solving large problems.  The best algorithms are *optimal* because they solve in $O(n)$ or $O(n\log n)$ time or memory, for data size $n$.  While optimal performance is not possible for some problems, algorithms which scale well with $n$ have a chance of solving the biggest, hardest problems in areas where mathematics is applied.

The ideal presentation might explain, and show concretely with examples, how an optimal (or near-optimal, or best-known) discrete or continuous algorithm works.  Each presentation should at least to try to clarify the size $n$ of the data to which the algorithm applies.  Presenters should explain how the run time, amount of computation, or amount of memory of the algorithm depends on the size $n$ of the data.

Beyond such basic expectations the talks should be diverse and the topics very wide-ranging!  See some possible topics below; there must be many more I don't know about.

Big O notation will often be used in presentations here, but the goal is *not* to create a theory of complexity course.  See [CS 611 Complexity of Algorithms](https://catalog.uaf.edu/courses/cs/) for that.

## possible topics

  * iterative linear algebra for sparse matrices (Krylov, etc.)
  * fast Fourier transform (FFT)
  * fast sorting algorithms
  * multigrid for solving partial differential equations
  * fast multipole methods for interacting particle systems
  * sparsity-exploiting direct solvers in linear algebra
  * fast integer multiplication, convolutions, etc.
  * spectral methods for differential equations
  * limited-memory optimization schemes
  * geometric algorithms in computer graphics (e.g. [here](https://www.cs.princeton.edu/courses/archive/fall04/cos226/lectures/geometry.4up.pdf))
  * graph algorithms (?)
  * monte carlo algorithms (?)

## <a id="schedule"></a> schedule of talks

| Date   | Speaker         | Title  |
|--------|-----------------|--------|
| 19 Jan | none            |        |
| 26 Jan | [Ed Bueler](https://bueler.github.io/) | [Making ice sheet models scale properly](slides/bueler-oxfordmg2023.pdf) |
| 2 Feb  | none            |        |
| 9 Feb  | none            |        |
| 16 Feb | none            |        |
| 23 Feb | [Ed Bueler](https://bueler.github.io/) | [Which linear systems can be solved optimally?](slides/bueler-optimal-linear.pdf) |
| 2 Mar  | Glen Woodworth  | An algorithm for graph isomorphism |
| 9 Mar  | none            |        |
| 23 Mar | none            |        |
| 30 Mar | Victor Devaux-Chupin | FFTs and numerical applications in geophysics |
| 6 Apr  | Austin Smith    | Limited-memory optimization |
| 13 Apr |                 |        |
| 20 Apr |                 |        |
| 27 Apr |                 |        |
| 4 May  |                 |        |
