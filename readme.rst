================================
Reactor Physics Benchmark Models
================================

This repository contains a collection of benchmark models for the OpenMC and
other Monte Carlo particle transport codes. The following benchmark models are
currently available:

doppler-defect
  Benchmark for Doppler reactivity defect by Russell Mosteller. Described in
  LA-UR-06-2968_.

icsbep
  Problems from the `International Handbook of Evaluated Criticality Safety
  Benchmark Experiments`_.

indc-usa-107
  Simple pin-cell model to test S(a,b) treatment in Monte Carlo codes. See
  `INDC(USA)-107`_.

mc-performance
  The `Monte Carlo Performance Benchmark`_ originally proposed by J. Eduard
  Hoogenboom and William Martin.

opr
  A BOL model of a Optimized Power Reactor 1000 (OPR1000) from South Korea. See
  Lee M.J. et al., "Monte Carlo Reactor Calculation with Substantially Reduced
  Number of Cycles", *Proceedings of PHYSOR 2012*, Knoxville, TN (2012).

source-convergence
  The `OECD/NEA Source Convergence Benchmarks`_ which include a checkerboard
  storage of assemblies, a pincell array with irradiated fuel, three thick
  one-dimensional slabs, and an array of interacting spheres.

takeda
  The `OECD/NEA 3-D Neutron Transport Takeda Benchmarks'_ which include a set of
  problems proposed by the Osaka University in 1988, including keff, rod worths,
  and flux distributions for four 3-D transport models.  The four models include
  a small LWR (model 1), a small FBR (model 2), an axially heterogeneous FBR
  (model 3), and finally a small FBR with Hexagonal-Z geometry (model 4).

.. _LA-UR-06-2968: http://mcd.ans.org/jb/bench/Doppler/Overview.pdf

.. _International Handbook of Evaluated Criticality Safety Benchmark Experiments: http://icsbep.inel.gov/handbook.shtml

.. _INDC(USA)-107: http://www-nds.iaea.org/publications/indc/indc-usa-0107.pdf

.. _Monte Carlo Performance Benchmark: http://www.oecd-nea.org/dbprog/MonteCarloPerformanceBenchmark.htm

.. _OECD/NEA Source Convergence Benchmarks: http://www.oecd-nea.org/science/wpncs/convergence/specifications/index.html

.. _OECD/NEA 3-D Neutron Transport Takeda Benchmarks: https://www.oecd-nea.org/science/docs/1990/neacrp-l-1990-330.pdf