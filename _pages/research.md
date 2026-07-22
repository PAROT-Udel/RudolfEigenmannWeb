---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

<h3>Machine Learning Driven Program Optimization</h3>
<img src="../images/research/AI.jpg" width="300" 
     height="300" alt="AI">

Achieving high performance on today's processors requires compiler optimizations that match the structure of the program and the characteristics of the target architecture. Transformations such as loop interchange, tiling, unrolling, vectorization, and parallelization can improve data locality, expose concurrency, and reduce execution time. However, their effects are not independent: an optimization that benefits one application or architecture may provide little benefit, or even degrade performance, when combined with other transformations. The number and ordering of candidate transformations therefore create a large, architecture-dependent optimization space.

This research investigates machine-learning-guided methods for navigating this space. These methods combine program features with compile-run feedback to evaluate candidate transformations for both correctness and performance. By learning from measured execution time and the outcomes of previous configurations, the optimization process can focus on promising combinations instead of relying on exhaustive search. The goal is to identify high-performing optimization sequences with fewer costly evaluations while preserving the behavior of the original program.

<b>Research Staff: Miguel Rosas</b>

---------------------------------------------------------------------------------------------------

<h3>DARWIN -- Delaware Advanced Research Workforce and Innovation Network</h3>
<img src="../images/research/DARWIN.jpg" width="300" 
     height="300" alt="DARWIN">

DARWIN is a compute and storage resource supporting computational and data-intensive research at the University of Delaware and in the Delaware Region. DARWIN is funded by an NSF MRI (Major Research Instrumentation) grant.
For more information, see the <a href="https://dsi.udel.edu/core/computational-resources/darwin">DARWIN project page</a>

---------------------------------------------------------------------------------------------------
<h3>The Xpert Network --A Peer Network for the exchange of computational best practices and support environments</h3>

<img src="../images/research/xpert.png" width="300" 
     height="300" alt="xpert">
Through a series of online and face-to-face meetings we are aiming to create synergy among teams that assist researchers in developing, optimizing, and running computational and data-intensive applications. We also connect developers of tools that help accomplish these tasks. We welcome participation from large, national projects as well as from individuals that assist computational researchers or develop supporting environments.
For more information, see the <a href="https://sites.udel.edu/xpert-cdi/">project page</a>
<a href="https://nsf.gov/awardsearch/showAward?AWD_ID=1833846">NSF Award Page</a>
<b>Research Staff: Parinaz Barakhshan</b>

----------------------------------------------------------------------------------------------------
<h3>Real-Application Benchmarks for High-Performance Computing</h3>

<img src="../images/research/spec30logo.jpg" width="300" 
     height="300" alt="spec30">

We are creating HPC benchmarks that are representative of real-world applications. This is a collaboration with the Standard Performance Evaluation Corporation, <a href="http://spec.org">SPEC</a> and Indiana University. <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1842623">NSF award page</a>. <a href="https://www.udel.edu/udaily/2020/june/sunita-chandrasekaran-rudi-eigenmann-supercomputer-benchmarks/">News release</a>

<b>Collaborators: </b> <a href="https://www.eecis.udel.edu/~schandra/">Sunita Chandrasekaran</a>, <a href="https://itnews.iu.edu/people/henschel.php">Robert Henschel</a>

----------------------------------------------------------------------------------------------------

<h3>Cetus Source-to-Source Compiler Infrastructure</h3>
<img src="../images/research/cetus.png" width="300" 
     height="300" alt="cetus">
 
 Cetus is a compiler and transformation infrastructure for transforming C source code. The original purpose of Cetus was for automatic parallelization - translation of C code into C code annotated with OpenMP directives. Many other uses of the translator have emerged, such as the translation of OpenMP programs into CUDA and MPI. Cetus is being maintained as a community infrastructure and has been used for many projects worldwide (see the list of publications on the Cetus web page).
The Cetus project is a collaboration with Purdue University. NSF awards:
<a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=0707931">0707931</a>
<a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=1405954">1405954</a>

<a href="https://sites.udel.edu/cetus-cid/">Cetus Website</a>

<b>Research Staff: </b> <a href="https://akshayud.me">Akshay Bhosale</a>, Parinaz Barakhshan, Jan Sher Khan, Hao Wang  
<b>Collaborators: </b> <a href="https://engineering.purdue.edu/~smidkiff/">Samuel Midkiff</a>, Milind Kulkarni.

----------------------------------------------------------------------------------------------------
<h3>COMPILE-TIME AUTOMATIC PARALLELIZATION OF SUBSCRIPTED SUBSCRIPTS USING RECURRENCE ANALYSIS</h3>
<img src="../images/research/programAnalysis.jpeg" width="300" 
     height="300" alt="cetus">
 
In this project we develop novel compiler analysis techniques that gather information from the program that enables parallelization of code that could not be parallelized in the past. Our current focus in on analyzing properties of the content of subscript arrays.

<a href="https://sites.udel.edu/cetus-cid/">Project Site</a>
<b>Research Staff: </b> <a href="https://akshayud.me">Akshay Bhosale</a>


----------------------------------------------------------------------------------------------------

<h3>Integrating iCetus (Interactive Cetus) with the CaRV (Capture, Replay & Validate) Tool</h3>
<img src="../images/research/interactive.png" width="300" 
     height="300" alt="cetus">
 
After developing iCetus, designed to facilitate the use of auto-parallelization techniques and leverage analysis results from Cetus—an ANSI C source-to-source auto-parallelizer—and applying manual parallelization to the code, we are integrating iCetus capabilities with the CaRV tool. CaRV expedites experimentation on code sections and validates the optimizations applied to those sections. The integration project, while facilitating the application of various types of optimizations to the code, aims to expedite the optimization process and ensure the validation of applied optimizations.

<b>Research Staff: </b> <a href="https://akshayud.me">Parinaz Barakhshan</a>

----------------------------------------------------------------------------------------------------

<nbsp>

<!-- {% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %} -->
