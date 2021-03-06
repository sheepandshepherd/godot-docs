.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Semaphore.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Semaphore:

Semaphore
=========

**Inherits:** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

A synchronization Semaphore.

Member Functions
----------------

+------------------------+-----------------------------------------------+
| :ref:`int<class_int>`  | :ref:`post<class_Semaphore_post>` **(** **)** |
+------------------------+-----------------------------------------------+
| :ref:`int<class_int>`  | :ref:`wait<class_Semaphore_wait>` **(** **)** |
+------------------------+-----------------------------------------------+

Description
-----------

A synchronization Semaphore. Element used in multi-threadding. Initialized to zero on creation.

Member Function Description
---------------------------

.. _class_Semaphore_post:

- :ref:`int<class_int>` **post** **(** **)**

Lowers the :ref:`Semaphore<class_semaphore>`, allowing one more thread in.

.. _class_Semaphore_wait:

- :ref:`int<class_int>` **wait** **(** **)**

Tries to wait for the :ref:`Semaphore<class_semaphore>`, if its value is zero, blocks until non-zero.


