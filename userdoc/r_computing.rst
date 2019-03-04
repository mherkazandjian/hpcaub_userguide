The R environment
-----------------

Summary
^^^^^^^

In this guide the following will be described:

  - how to run R in a terminal on the HPC cluster
  - how to submit a R job
  - how to launch R studio
  - how to run a R server and connect to it from your browser as a client (under development)

How to launch R studio
++++++++++++++++++++++

To launch R stuid, an interactive job must be submitted. (see "add link here")
After connecting to the vnc session of the interactive job, R studio can be
launched using the command:

.. code-block:: bash

    singularity exec /gpfs1/apps/sw/singularity/containers/rstudio/latest rstudio

.. figure:: imgs/interactive_work_on_compute_nodes.png
   :scale: 100 %
   :alt:
