---
layout: post
title: 03 Introduction to NumPy
---

We saw in the
[Introduction to Python]({{site.baseurl}}/2016/01/19/02_Introduction_to_Python/)
that the Python language has the control and data structures to do
numerical calculations. For instance, a vector $$\vec{r} = (x, y, z)$$
denoting the position of a particle could be represented as a Python
list `[x, y, z]`.

When it comes to doing numerical work, Python by itself is rather
slow. By slow we mean compared to languages like C and Fortran, which
benefit from being compiled languages in which a program is
preprocessed into machine code by a compiler. Python by contrast is an
interpreted language, in which each line in a program is fed to the
Python interpreter in sequence, then executed. The flexiblity and ease
of use that come with Python come at the cost of pure performance.

However, though Python code itself may be slow, Python can be used to
run code that is written in a compiled language and already
compiled. We will use a library (a.k.a., a Python **module**) that does
exactly this underneath the hood to get fast performance for numerical
operations on arrays: We load the [NumPy](http://www.numpy.org/) module:

{% highlight python %}
import numpy
{% endhighlight %}

# Tutorial

The class will be live-coded in a Jupyter notebook. The annotated
notebook will be available after the lesson.
