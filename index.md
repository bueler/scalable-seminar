<head>
<script type="text/x-mathjax-config">
  MathJax.Hub.Config({
      extensions: ["tex2jax.js"],
      tex2jax: {
          inlineMath: [ ['$','$'], ["\\(","\\)"] ],
          processEscapes: true,
          processRefs: true,
          processEnvironments: true
      },
      TeX: { equationNumbers: { autoNumber: "AMS" } }
  });
</script>
<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>
</head>

This is the draft page of **Math 692 Graduate Seminar** in Spring 2023, in the [Dept. of Mathematics and Statistics](http://www.uaf.edu/dms/) at the [University of Alaska Fairbanks](http://www.uaf.edu/).

## seminar organizer

[Ed Bueler](http://bueler.github.io/).  Email me at [elbueler@alaska.edu](mailto:elbueler@alaska.edu).

## proposed content

My idea is to have a seminar where we can learn about any mathematical algorithms, or even algorithms more generally, which are aimed at solving large problems.  Each presentation would be expected to try to clarify the size $n$ of the data to which the algorithm applies, and try to understand or estimate how the time, amount of computation, or amount of memory depends on the size $n$ of the data.  Beyond that basic expecation the topics could be very wide-ranging.

Many of the best algorithms are *optimal* because they solve in $O(n)$ or $O(n\log n)$ time.  (Big O notation might often be used in presentations here, but the goal is not a course on the theory of complexity.  See [CS 611 Complexity of Algorithms](https://catalog.uaf.edu/courses/cs/) for that.)  Can we concretely understand discrete or continuous algorithms that have a chance of solving big problems in important areas of applied mathematics?

### possible topics

  * iterative linear algebra for sparse matrices
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
  * fast monte carlo implementations (?)

### course details

Time and place: to be determined

CRN: to be determined

Credits: 1.0, but **non-credit attendance is encouraged*.  If you want to take the seminar for credit then you should expect to give a least one presentation.
