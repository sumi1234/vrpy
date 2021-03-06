`VRPy` Documentation
====================

`VRPy` is a python framework for solving Vehicle Routing Problems (VRP) including:

-   the Capacitated VRP (CVRP),
-   the CVRP with resource constraints,
-   the CVRP with time windows (CVRPTW),
-   the CVRP with simultaneous distribution and collection (CVRPSDC),
-   the CVRP with heterogeneous fleet (HFCVRP).

Check out section :ref:`vrp` to find more variants and options.

`VRPy` relies on the well known NetworkX_ package (graph manipulation), as well as on cspy_, a library for solving the resource constrained shortest path problem.

.. _NetworkX: Graph manipulation and creation.
.. _cspy: https://pypi.org/project/cspy/

.. toctree::
   :maxdepth: 2
   :caption: User Guide
   
   getting_started
   how_to
   vrp_variants
   solving_options
   examples
   api
   mathematical_background

Authors
=======

Romain Montagné (r.montagne@hotmail.fr)

David Torres Sanchez (d.torressanchez@lancs.ac.uk)

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
