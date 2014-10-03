cluster-utils
=============

Tools for use in cluster environments.

Manifest
--------

scripts/

Scripts
-------

* build-mpirun-configfile.py - builds a configfile for use with MPICH2 mpirun
                             - used as a workaround to set the HOSTNAME and CUDA_VISIBLE_DEVICES environment variables properly on the cbio-cluster
