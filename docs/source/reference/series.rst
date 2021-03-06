.. _api.series:

======
Series
======
.. currentmodule:: databricks.koalas

Constructor
-----------
.. autosummary::
   :toctree: api/

   Series

Attributes
----------

.. autosummary::
   :toctree: api/

   Series.index

.. autosummary::
   :toctree: api/

   Series.dtype

Conversion
----------
.. autosummary::
   :toctree: api/

   Series.astype

.. _api.series.stats:

Computations / Descriptive Stats
--------------------------------
.. autosummary::
   :toctree: api/

   Series.abs
   Series.corr
   Series.count
   Series.kurt
   Series.max
   Series.mean
   Series.min
   Series.skew
   Series.std
   Series.sum
   Series.var
   Series.kurtosis
   Series.unique
   Series.value_counts

Reindexing / Selection / Label manipulation
-------------------------------------------
.. autosummary::
   :toctree: api/

   Series.head
   Series.rename
   Series.reset_index

Missing data handling
---------------------
.. autosummary::
   :toctree: api/

   Series.isna
   Series.notna
   Series.dropna
