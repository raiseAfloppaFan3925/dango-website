
Memory System
=============

Normally in any other language, this is where you would be introduced to variables, data types, and syntax.
However, Dango works a bit differently.

Dango does not have variables, since it works on a stack. The values you see that are connected to sticks
(these things, ``----``), called dumplings for lack of a better word, are pushed onto the stack in
right-to-left order.

.. code-block:: text
    
    (1)(2)(3)----

.. code-block:: text
    :caption: Stack of the example from above

    top
    1
    2
    3
    bottom

This means that you have to be wary of the stack whenever you are using instructions or functions that rely on them.
