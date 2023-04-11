.. OpenSees documentation master file, created by
   sphinx-quickstart on Mon Jan 13 09:11:34 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

======================
OpenSees Examples
======================

The Open System for Earthquake Engineering Simulation (OpenSees) is a software framework for simulating the dynamic response of structural and geotechnical systems. OpenSees was originally developed as the computational platform for research in performance-based earthquake engineering at the Pacific Earthquake Engineering Research Center. It is now widely used as a finite element application to study response of structures across all natural hazards including Fire, Wind, Earthquake, and Wave action due to Tsunami or Storm Surge.

This document provides examples ranging from the simple to convoluted!

.. _introductoryStructuralExamples:

.. toctree::
   :caption: Simple Elastic Structural Examples
   :maxdepth: 2
   :numbered: 2

   introductoryStructural/elasticTruss/basicTruss
   introductoryStructural/elasticCantileverColumn/elasticColumn


.. toctree::
   :caption: Nonlinear Structural Examples
   :maxdepth: 2
   :numbered: 2

   nonlinearStructural/2dFrame33/frame

   
.. |cantilever3| image:: ./introductoryStructural/elasticCantileverColumn/figures/elasticCantileverColumn.png 
   :width: 150pt
   :height: 300pt
	    
OpenSees Example 2b. Nonlinear Cantilever Column: Uniaxial Inelastic Section

.. list-table:: 
   :class: borderless

   * - |cantilever3|
     - first example of nonlinear model, set nonlinearity at section level
     - Models:
	     * nonlinearBeamColumn element
	     * unixial section
     - Analysis:
	     * static pushover
	     * dynamic earthquake input



2D Frame 3 Stories, 3 Bays

.. list-table:: 
   :class: borderless

   * - |cantilever3|
     - Objectives
             * 2D frame of fixed geometry: 3-story, 3-bay
	     * nodes and elements are defined manually, one by one
     - Models:
	     * Reinforced-Concrete Section
	     * Steel W-Section
	     * Elastic uniaxial section
             * Inelastic uniaxial section
             * Inelastic fiber section
     - Analysis:
             * Static reversed cyclic analysis
	     * Dynamic sine-wave input analysis (uniform excitation)
	     * Dynamic earthquake-input analysis (uniform excitation)
	     * Dynamic sine-wave input analysis (multiple-support excitation)
	     * Dynamic earthquake-input analysis (multiple-support excitation)
	     * Dynamic bidirectional earthquake-input analysis (uniform excitation)

