
Getting Started
===============

.. note::

    This section assumes that you have already installed Dango. If not, then see :doc:`../installation`.

To start an interactive session, simply run ``dango`` in the command line. A limitation of this though is that you can
only enter one line.

.. code-block:: text

    $ dango

     _|_
    /@@@\  | Dango 0.9.0
    \@@@/  |
    /%%%\  | Documentation: https:/raiseAfloppaFan3925.github.io/dango
    \%%%/  | 'exit' to exit
    /***\  |
    \***/  | If you find any bugs, please report them at https://github.com/raiseAfloppaFan3925/dango-esolang/issues
      |    |
      |

    --(O)(O)(O) > (1)(2)----
    2
    --(0)(0)(0) > eat (')(Hello, world!)----
    Hello, world!
    ()
    --(0)(0)(0) >

To run a file, put the path to it as the first argument of the ``dango`` command.

.. code-block:: text

    $ dango file.dango

With this, you can pass additional arguments AFTER the path to your program, which can be used in ``(:env-args)``.

.. toctree::

    memory
    syntax
