# GWS_code
Supplementary Python code for paper on mining heat extremes using Global Warming Scaling

General
-------
``hw.ipynb`` provides a general object-oriented framework for automatically processing daily temperature series.

Pre-processing
--------------
``anomalies.ipynb`` is a Python notebook in which the LGWR is calculated as descibed in the article.
``scaling.ipynb`` is a Python notebook in which the LGWR is applied in scaling an observational temperature series for Brussels to GWL2.0.

Mining
------
``mining_selected_sims.ipynb`` contains code for mining years of extreme heat from the initial selection of EURO-CORDEX simulations using GWS targets.

Impact analysis
---------------
WBGT and productivity loss calculations for the demo year are contained in ``productivity_2060.ipynb``.
Fire hazard calculations for the demo year are contained in ``fwi_2060.ipynb``.
Modelling of Zeeschelde water temperatures during the demo year is done in ``Zeeschelde_temp2060.ipynb``.

All necessary data can be accessed freely or can be made available upon request. Some external Python packages may need to be installed for the impact analysis.
