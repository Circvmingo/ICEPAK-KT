Initial Thoughts
================

.. _Initial Thoughts:

Main Interface
--------------

This software has the capability to be very powerful. However, the
software is laid out in a rather unintuitive manner. The UI somehow
looks like a worse version of ANSYS SpaceClaim, there are so many
sub-windows covering the screen that the software becomes borderline
unusable, and the viewport navigation is downright atrocious.

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

