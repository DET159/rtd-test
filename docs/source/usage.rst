Objective 1: Department of Air Force and AFROTC Grade Structure and Insignia
=====

.. _installation:

Air Force Enlisted Grade Structure
------------
.. image:: images/Rank_1.png
   :width: 800
..
   To use Lumache, first install it using pip:


   .. code-block:: console

   (.venv) $ pip install lumache

Space Force Enlisted Grade Structure
------------
.. image:: images/Rank_2.png
   :width: 454


Air Force and Joint Officer Grade Structure
------------
.. image:: images/Rank_3.png
   :width: 800


AFROTC Cadet Grade Structure
------------
.. image:: images/Rank_3.png
   :width: 775





.. 
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

