Things to study
---------------

* Python basics

  * Basic flow-control: ``if``, ``elif``, ``else``
  * Basic loop constructs: ``for i in ...``
  * Mutability vs. Immutability (and be able to give examples of mutable and
    immutable objects)
  * Lists vs. dictionaries
  * Defining functions and passing arguments
  * Running python scripts from the command line
  * Know how to raise and except exceptions

* Ipython

  * Magic commands such as ``%timeit``, ``%run`` and ``%debug``
  * Using the question-mark operator to get help

* Numpy

  * Know some array creation functions (``zeros``, ``ones``, ``empty`` etc..)
    and what kind of arrays these create
  * Indexing and Slicing (multi-dimensional) arrays
  * Difference between views and copies

* Matplotlib

  * Plotting data (``plot`` command)
  * Modifying a plot: adding labels, ticks and a title
  * Plot with different symbols (e.g. triangles)
  * Be able to use the subplot command

* Unit-testing

  * Understand the merits of unit-testing
  * Know three assert methods of the ``unittest`` package (e.g.
  * ``assertEqual``, ``assertTrue`` and ``assertRaises``) and what they check
  * Be able to write a simple unit-test
  * Know how to run tests with ``nosetests``

* Git

  * Understand the merits of version control (i.e. why you should use it)
  * Be familiar with a basic git workflow (know a few basic commands):

    * ``git clone``
    * ``git add``
    * ``git commit``
    * ``git push``
    * ``git pull``

  * Be able to describe the difference between a centralized and distributed
    version control system.

* Debugging Profiling and Optimization

  * Be able to launch a debugger in one of the many ways (e.g. using the
    ``--ipdb`` option of nosetests or the ``%debug`` magic of IPython.
  * Know three basic debugger commands (e.g. ``continue``, ``step`` and
    ``down``)
  * Know what a profiler is and review the ``%prun`` IPython magic command
  * Be aware that looking for bottlenecks by measuring is the first step in
    optimization.

* Parallel programming

  * Describe the difference between processes and threads
  * Know the term: "embarrassingly parallel"
  * Be able to use the ``Pool`` class from the ``multiprocessing`` package
  * Know about race conditions and deadlocks
  * Know about the Global Interpreter Lock (GIL) and what implications this has
    for Python.

* Interfacing with C

  * Be able to mention Cython and it's two main use-cases
