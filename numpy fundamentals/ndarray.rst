.. code:: ipython3

    import numpy as np

.. code:: ipython3

    #  ndarray
    # a special datatype in python
    # element wise properties

.. code:: ipython3

    # declare an nd array
    
    array_a = np.array([1,2,3])
    

.. code:: ipython3

    array_a




.. parsed-literal::

    array([1, 2, 3])



.. code:: ipython3

    type(array_a)




.. parsed-literal::

    numpy.ndarray



.. code:: ipython3

    # nd array is object of array(name of function)

.. code:: ipython3

    array_a.shape




.. parsed-literal::

    (3,)



.. code:: ipython3

    array_b = np.array([[1,2,3],[4,5,6]])

.. code:: ipython3

    array_b.shape




.. parsed-literal::

    (2, 3)



.. code:: ipython3

    type(array_b)




.. parsed-literal::

    numpy.ndarray



.. code:: ipython3

    print(array_b)


.. parsed-literal::

    [[1 2 3]
     [4 5 6]]
    

.. code:: ipython3

    print(array_a)


.. parsed-literal::

    [1 2 3]
    

.. code:: ipython3

    array_c = np.array(14)

.. code:: ipython3

    type(array_c)




.. parsed-literal::

    numpy.ndarray



.. code:: ipython3

    array_c.shape




.. parsed-literal::

    ()



.. code:: ipython3

    array_d = np.array([15])

.. code:: ipython3

    type(array_d)




.. parsed-literal::

    numpy.ndarray



.. code:: ipython3

    print(array_d)


.. parsed-literal::

    [15]
    

.. code:: ipython3

    array_d.shape




.. parsed-literal::

    (1,)



