.. _majority_vote:

🗳️ Majority Vote 
=================

.. image:: ../_static/img/Relative_Majority.png
   :alt: Alternative text
   :align: center

The consensus using the majority vote consists of the Relative Majority, this means that the final cell class will be assigned as the class with the most agreement.
If the final results are tied, the cell will be labelled as **No Consensus**.
If the final agreement is lower than the :code:`min_agreement` value specified by the user will be labelled as **No Consensus**.
In case of using an ontology, cell classes are converted to their broader class before computing the consensus.


