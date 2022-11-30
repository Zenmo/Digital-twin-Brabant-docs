Data
====
This page inidactes all data sources used. Primarly data from publicaly available open-sources have been used. The only exception on this is the low voltage transformer capacity, which has been distributed under NDA.

The public data can be downloaded, directly from its sources, or the actual data used in the model from the github repositories.

* `Get data neighborhood model <https://github.com/ZEnMo/Brabant-buurt-serious-game/tree/main/data/>`_ 
* `Get data province model <https://github.com/ZEnMo/Brabant-systeem-integratie-model/tree/main/Data/>`_ 

.. _List-of-model-data:

List of all data sources
-------------------------



.. list-table:: **Data sources**
   :widths: 60 30 30 30
   :header-rows: 1
   
   * - Description
     - Source
     - Year
     - Accesability
   * - **Neighborhood characteristics**
     -
     - 
     - 
   * - Building characteristics
     - BAG
     - 2021
     - Open data
   * - Building insulation levels
     - RVO
     - 2021
     - Open data
   * - Demographic characteristics 
     - CBS
     - 2021
     - Open data
   * - Grid topology
     - Enexis
     - 2021
     - Open data
   * - Low-voltage transformer capacity
     - Enexis
     - 2022
     - Under NDA
   * - Building locations
     - BAG / PDOK
     - 2021
     - Open data
   * - **Province characteristics**
     -
     - 
     - 
   * - Neighborhood demarcation
     - PDOK
     - 2021
     - Open data
   * - Grid topology
     - Enexis
     - 2021
     - Open data
   * - Renewable generation sources
     - RVO SDE++
     - 2022
     - Open data          
   * - Heat sources
     - `Startanalyse Expertise Centrum Warmte <https://www.warmteatlas.nl/viewer/app/Warmteatlas/v2?debug=false>`_
     - 2021
     - Open data     
   * - **Energy supply and demand**
     - 
     - 
     - 
   * - Annual household energy demand (DHW, room heating, electricity)
     - `PBL Vesta MAIS <https://www.pbl.nl/sites/default/files/downloads/pbl-2021-functioneel-ontwerp-vesta-mais-5.0-4583.pdf>`_
     - 2021
     - Open-source model
   * - Annual neighborhood energy demand per strategy
     - `Startanalyse PBL Vesta MAIS <https://themasites.pbl.nl/leidraad-warmte/2020/>`_
     - 2020
     - Open-source model     
   * - DHW hourly profile
     - DHWCalc
     - 2005
     - Open-source model     
   * - Travel behavior patterns
     - Albatross
     - 2022
     - Closed scientific model     
   * - Electricity hourly demand profile
     - NEDU
     - 2021
     - Open data     
   * - Gas hourly demand profile
     - NEDU
     - 2021
     - Open data
   * - Weather data
     - KNMI
     - 2019
     - Open data 
   * - **Costs**
     - 
     -   
     -
   * - Cost assumptions
     - PBL Vesta MAIS
     - 2021
     - Open-source model

Subtitute non-public data
~~~~~~~~~~~~~~~~~~~~~~~~~~
To substitute this data for public usage of the model the transformer capacity can be seen as a funtion from the connected households, averiging a capacity of 1.5kW per household. 

.. _cost-assumptions:

Cost assumptions
-----------------------

.. _technology-characteristics:

Technology chacarteristics
--------------------------
