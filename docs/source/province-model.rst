Province model
==================

.. _Province-model-structure:

Province model structure
-------------------------

The provincial model alligns data and agents on multiple levels. On the supply side agents are created for all individual wind turbines, and solar power plants (above 0.2MW), and other renewable energy generation projects from the SDE+ database that are currently finished.
On the demand side the smallest geographical level are neighborhoods. The model represents all neighborhoods in the province and calculates their demand based on number of households, inhabitants, and vehicles. Furthermore small scale PV is calculated on this level. The next level are municipalities, which include calculations on industrial and agricultural energy consumption, as these are not available on a neighborhood level.
In terms of infrastructure the model contains high-to-medium voltage transformers and corresponding grids. Based on the care areas of these transformers the supply and demand of generation units, neighborhoods, and municipalities are aggregated on a transformer.


.. _energy-calculations:

Energy Calculations
-------------------

Energy supply and demand are calculated on an hourly level. Supply depends on weather conditions for wind and solar projects and general grid supply. Demand is based on NEDU consumption profiles for households, industry, and agriculture. These are aggregated on the high-to-medium voltage transformers and compared to the max transformer capacity.
Additional electricity demand arises if the number of heat pumps or electric vehicles is increased, ultimately leading to grid congestion on the transformers.


