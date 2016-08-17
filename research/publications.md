<!--
.. title: Publications
.. slug: publications
.. date: 2013/03/01 10:26:17
.. tags:
.. link:
.. description:
-->

2016
====

Weight Adjusted Discontinuous Galerkin Methods: Curvilinear Meshes
---------------------------------------------------------------------------------------

J. Chan, **R. J. Hewett**, and T. Warburton,  
submitted to *the SIAM Journal on Scientific Computing*.  
[link]
[pdf]
[[arxiv]](http://arxiv.org/abs/1608.01944)
<a href="javascript:toggle('sisc2016b_text','sisc2016b_link');"id="sisc2016b_link">
   [show abstract]
</a>

<div id="sisc2016b_text" style="display:none;">
   Traditional time-domain discontinuous Galerkin (DG) methods result in large storage
   costs at high orders of approximation due to the storage of dense elemental matrices. 
   In this work, we propose a weight-adjusted DG (WADG) methods for curvilinear meshes 
   which reduce storage costs while retaining energy stability. A priori error estimates 
   show that high order accuracy is preserved under sufficient conditions on the mesh, 
   which are illustrated through convergence tests with different sequences of meshes. 
   Numerical and computational experiments verify the accuracy and performance of WADG 
   for a model problem on curved domains. 
</div>

Weight Adjusted Discontinuous Galerkin Methods: Wave Propagation in Heterogeneous Media
---------------------------------------------------------------------------------------

J. Chan, **R. J. Hewett**, and T. Warburton,  
submitted to *the SIAM Journal on Scientific Computing*.  
[link]
[pdf]
[[arxiv]](http://arxiv.org/abs/1608.01944)
<a href="javascript:toggle('sisc2016a_text','sisc2016a_link');"id="sisc2016a_link">
   [show abstract]
</a>

<div id="sisc2016a_text" style="display:none;">
   Time-domain discontinuous Galerkin (DG) methods for wave propagation require 
   accounting for the inversion of dense elemental mass matrices, where each mass 
   matrix is computed with respect to a parameter-weighted L2 inner product. In 
   applications where the wavespeed varies spatially at a sub-element scale, these 
   matrices are distinct over each element, necessitating additional storage. In 
   this work, we propose a weight-adjusted DG (WADG) method which reduces storage
   costs by replacing the weighted L2 inner product with a weight-adjusted inner 
   product. This equivalent inner product results in an energy stable method, but
   does not increase storage costs for locally varying weights. A-priori error 
   estimates are derived, and numerical examples are given illustrating the 
   application of this method to the acoustic wave equation with heterogeneous 
   wavespeed. 
</div>

Reduced Storage Nodal Discontinuous Galerkin Methods on Semi-structured Prismatic Meshes
----------------------------------------------------------------------------------------

J. Chan, **R. J. Hewett**, Z. Wang, and T. Warburton,  
submitted to *Computers and Mathematics With Applications*.  
[link]
[pdf]
[[arxiv]](http://arxiv.org/abs/1607.03399)
<a href="javascript:toggle('camwa2016_text','camwa2016_link');"id="camwa2016_link">
   [show abstract]
</a>

<div id="camwa2016_text" style="display:none;">
   We present a high order time-domain nodal discontinuous Galerkin method for
   wave problems on hybrid meshes consisting of both wedge and tetrahedral 
   elements. We allow for vertically mapped wedges which can be deformed along 
   the extruded coordinate, and present a simple method for producing 
   quasi-uniform wedge meshes for layered domains. We show that standard mass 
   lumping techniques result in a loss of energy stability on meshes of 
   vertically mapped wedges, and propose an alternative which is both energy 
   stable and efficient. High order convergence is demonstrated, and comparisons 
   are made with existing low-storage methods on wedges. Finally, the 
   computational performance of the method on Graphics Processing Units is 
   evaluated.
</div>

2015
====

Optimized finite difference coefficients for the Helmholtz equation
-------------------------------------------------------------------

M. N'Diaye, **R. J. Hewett**, A. Atle, and H .Calandra,  
*85th Annual Meeting, SEG, Expanded Abstracts*, October, 2015.  
[link]
[pdf]
<a href="javascript:toggle('seg2015_text','seg2015_link');"id="seg2015_link">
   [show abstract]
</a>

<div id="seg2015_text" style="display:none;">
   Optimized finite difference (OFD) coefficients are often used to minimize
   numerical dispersion and to improve accuracy in finite difference (FD)
   solutions to partial differential equations (Lele (1992); Tam and Webb
   (1993); Jo et al. (1996); Liu and Sen (2010); Štekl and Pratt (1998)). We
   present a framework for deriving such coefficients which at once minimizes
   numerical dispersion and preserves convergence at low frequency. We compute
   optimal coefficients in each dimension and then assemble the optimal
   multi-dimensional stencil for the computational grid. We demonstrate the
   effectiveness of our OFD scheme by computing solutions to the Helmholtz
   equation below 3.5 points-per-wavelength (ppw).
</div>

SunPy--Python for solar physics
-------------------------------

The SunPy Community, S. J. Mumford, S. Christe, D. Pérez-Suárez,  J. Ireland, A. Y. Shih, 
A. R. Inglis, S. Liedtke, ** R. J. Hewett **, F. Mayer, K. Hughitt, N. Freij, 
T. Meszaros, S. M. Bennett, M. Malocha, J Evans, A. Agrawal, A. J.  Leonard, T. P. Robitaille, 
B. Mampaey, J. I. Campos-Rozo, and M. S. Kirk,  
*Computational Science and Discovery*, Volume 8, Issue 1, January, 2015.  
[link]
[pdf]
<a href="javascript:toggle('csd2015_text','csd2015_link');"id="csd2015_link">
   [show abstract]
</a>

<div id="csd2015_text" style="display:none;">
   This paper presents SunPy (version 0.5), a community-developed Python
   package for solar physics. Python, a free, cross-platform, general-purpose,
   high-level programming language, has seen widespread adoption among the
   scientific community, resulting in the availability of a large number of
   software packages, from numerical computation (NumPy, SciPy) and machine
   learning (scikit-learn) to visualization and plotting (matplotlib). SunPy
   is a data-analysis environment specializing in providing the software
   necessary to analyse solar and heliospheric data in Python. SunPy is
   open-source software (BSD licence) and has an open and transparent
   development workflow that anyone can contribute to. SunPy provides access
   to solar data through integration with the Virtual Solar Observatory (VSO),
   the Heliophysics Event Knowledgebase (HEK), and the HELiophysics Integrated
   Observatory (HELIO) webservices. It currently supports image data from
   major solar missions (e.g., SDO, SOHO, STEREO, and IRIS), time-series data
   from missions such as GOES, SDO/EVE, and PROBA2/LYRA, and radio spectra
   from e-Callisto and STEREO/SWAVES. We describe SunPy's functionality,
   provide examples of solar data analysis in SunPy, and show how Python-based
   solar data-analysis can leverage the many existing tools already available
   in Python. We discuss the future goals of the project and encourage
   interested users to become involved in the planning and development of
   SunPy.
</div>

2014
====

Preconditioning the 2D Helmholtz equation with polarized traces
---------------------------------------------------------------

L. Zepeda-Núñez, **R. J. Hewett**, and L. Demanet,  
*84th Annual Meeting, SEG, Expanded Abstracts*, October, 2014.  
[link]
[pdf]
<a href="javascript:toggle('seg2014_text','seg2014_link');"id="seg2014_link">
   [show abstract]
</a>

<div id="seg2014_text" style="display:none;">
   We present a domain decomposition solver for the 2D Helmholtz equation,
   with a special choice of integral transmission condition that involves
   polarizing the waves into one-way components. This refinement of the
   transmission condition is the key to combining local direct solves into an
   efficient iterative scheme, which can then be deployed in a
   high-performance computing environment. The method involves an expensive,
   but embarrassingly parallel precomputation of local Green’s functions, and
   a fast online computation of layer potentials in partitioned low-rank form.
   The online part has sequential complexity that scales sublinearly with
   respect to the number of volume unknowns, even in the high-frequency
   regime. The favorable complexity scaling continues to hold in the context
   of low-order finite difference schemes for standard community models such
   as BP and Marmousi2, where convergence occurs in 5 to 10 GMRES iterations.
</div>

2013
====

Time-stepping beyond CFL: a locally one-dimensional scheme for acoustic wave propagation
----------------------------------------------------------------------------------------

L. Zepeda-Núñez, **R. J. Hewett**, M. Rao, and L. Demanet,  
*83rd Annual Meeting, SEG, Expanded Abstracts*, September, 2013.  
[link]
[pdf]
<a href="javascript:toggle('seg2013a_text','seg2013a_link');"id="seg2013a_link">
   [show abstract]
</a>

<div id="seg2013a_text" style="display:none;">
   In this abstract, we present a case study in the application of a
   time-stepping method, unconstrained by the CFL condition, for
   computational acoustic wave propagation in the context of full waveform
   inversion. The numerical scheme is a locally one-dimensional (LOD)
   variant of alternating dimension implicit (ADI) method. The LOD method
   has a maximum time step that is restricted only by the Nyquist sampling
   rate. The advantage over traditional explicit time-stepping methods
   occurs in the presence of high contrast media, low frequencies, and
   steep, narrow perfectly matched layers (PML). The main technical point
   of the note, from a numerical analysis perspective, is that the LOD
   scheme is adapted to the presence of a PML. A complexity study is
   presented and an application to full waveform inversion is shown.
</div>

High-dimensional wave atoms and compression of seismic datasets
---------------------------------------------------------------

M. Leinonen, **R. J. Hewett**, X. Zhang, L. Ying, and L. Demanet,  
*83rd Annual Meeting, SEG, Expanded Abstracts*, September, 2013.  
[link]
[pdf]
<a href="javascript:toggle('seg2013b_text','seg2013b_link');"id="seg2013b_link">
   [show abstract]
</a>

<div id="seg2013b_text" style="display:none;">
   Wave atoms are a low-redundancy alternative to curvelets, suitable for
   high-dimensional seismic data processing. This abstract extends the wave
   atom orthobasis construction to 3D, 4D, and 5D Cartesian arrays, and
   parallelizes it in a shared-memory environment. An implementation of the
   algorithm for NVIDIA CUDA capable graphics processing units (GPU) is
   also developed to accelerate computation for 2D and 3D data. The new
   transforms are benchmarked against the Fourier transform for compression
   of data generated from synthetic 2D and 3D acoustic models.
</div>

2012
====

A Phase Field Method for Tomographic Reconstruction from Limited Data
---------------------------------------------------------------------

**R. J. Hewett**, I. H. Jermyn, M. T. Heath, and F. Kamalabadi,  
*Proceedings of the British Machine Vision Conference*, pp.
120.1-120.11, August, 2012.  
[link]
[pdf]
<a href="javascript:toggle('bmvc2012_text','bmvc2012_link');"id="bmvc2012_link">
   [show abstract]
</a>
<div id="bmvc2012_text" style="display:none;">
   Classical tomographic reconstruction methods fail for problems in which
   there is extreme temporal and spatial sparsity in the measured data.
   Reconstruction of coronal mass ejections (CMEs), a space weather
   phenomenon with potential negative effects on the Earth, is one such
   problem. However, the topological complexity of CMEs renders recent
   limited data reconstruction methods inapplicable. We propose an energy
   function, based on a phase field level set framework, for the joint
   segmentation and tomographic reconstruction of CMEs from measurements
   acquired by coronagraphs, a type of solar telescope. Our phase field
   model deals easily with complex topologies, and is more robust than
   classical methods when the data are very sparse. We use a fast
   variational algorithm that combines the finite element method with a
   trust region variant of Newton's method to minimize the energy. We
   compare the results obtained with our model to classical regularized
   tomography for synthetic CME-like images.
</div>

Intercomparison of the LASCO-C2, SECCHI-COR1, SECCHI-COR2, and Mk4 Coronagraphs
-------------------------------------------------------------------------------

R. A. Frazin, A. M. Vàsquez, W. T. Thompson, **R. J. Hewett**, P. Lamy,
A. Llebaria, A. Vourlidas, and J. Burkpile,  
*Solar Physics*, Volume 280, Issue 1, pp. 273-293, 2012.  
[link]
[pdf]
<a href="javascript:toggle('solphys2012_text','solphys2012_link');"id="solphys2012_link">
   [show abstract]
</a>
<div id="solphys2012_text" style="display:none;">
   In order to assess the reliability and consistency of white-light
   coronagraph measurements, we report on quantitative comparisons between
   polarized brightness [pB] and total brightness [B] images taken by the
   following white-light coronagraphs: LASCO-C2 on SOHO, SECCHI-COR1 and
   -COR2 on STEREO, and the ground-based MLSO-Mk4. The data for this
   comparison were taken on 16 April 2007, when both STEREO spacecraft were
   within 3.1° of Earth's heliographic longitude, affording essentially the
   same view of the Sun for all of the instruments. Due to the difficulties
   of estimating stray-light backgrounds in COR1 and COR2, only Mk4 and C2
   produce reliable coronal-hole values (but not at overlapping heights),
   and these cannot be validated without rocket flights or ground-based
   eclipse measurements. Generally, the agreement between all of the
   instruments' pB values is within the uncertainties in bright streamer
   structures, implying that measurements of bright CMEs also should be
   trustworthy. Dominant sources of uncertainty and stray light are
   discussed, as is the design of future coronagraphs from the perspective
   of the experiences with these instruments.
</div>

2010
----

A Robust Null Space Method for Linear Equality Constrained State Estimation
---------------------------------------------------------------------------

**R. J. Hewett**, M. T. Heath, M. D. Butala, and F. Kamalabadi,  
*IEEE Transactions on Image Processing*, Volume 58, Issue 8, pp. 3961-3971,
August, 2010.  
[link]
[pdf]
<a href="javascript:toggle('ieee2010_text','ieee2010_link');"id="ieee2010_link">
   [show abstract]
</a>
<div id="ieee2010_text" style="display:none;">
   We present a robust null space method for linear equality constrained
   state space estimation. Exploiting a degeneracy in the estimator
   statistics, an orthogonal factorization is used to decompose the problem
   into stochastic and deterministic components, which are then solved
   separately. The resulting dimension reduction algorithm has enhanced
   numerical stability, solves the constrained problem completely, and can
   reduce computational load by reducing the problem size. The new method
   addresses deficiencies in commonly used pseudo-observation or projection
   methods, which either do not solve the constrained problem completely or
   have unstable numerical implementations, due in part to the degeneracy
   in the estimator statistics. We present a numerical example
   demonstrating the effectiveness of the new method compared to other
   current methods.
</div>

Dynamic Three-Dimensional Tomography of the Solar Corona
--------------------------------------------------------

M. D. Butala, **R. J. Hewett**, R. A. Frazin, and F. Kamalabadi,  
*Solar Physics*, Volume 262, Issue 2, pp. 495-509, February, 2010.  
[link]
[pdf]
<a href="javascript:toggle('solphys2010_text','solphys2010_link');"id="solphys2010_link">
   [show abstract]
</a>
<div id="solphys2010_text" style="display:none;">
   Empirical, three-dimensional electron-density maps of the solar corona
   can be tomographically reconstructed using polarized-brightness images
   measured from ground- and space-based observatories. Current methods for
   computing these reconstructions require the assumption that the
   structure of the corona is unchanging with time. We present the first
   global reconstructions that do away with this static assumption and, as
   a result, allow for a more accurate empirical determination of the
   dynamic solar corona. We compare the new dynamic reconstructions of the
   coronal density during February 2008 to a sequence of static
   reconstructions. We find that the new dynamic reconstructions are less
   prone to certain computational artifacts that may plague the static
   reconstructions. In addition, these benefits come without a significant
   increase in computational cost.
</div>

2008
----

Multiresolution Analysis of Active Region Magnetic Structure and Its Correlation with the Mt. Wilson Classification and Flaring Activity
----------------------------------------------------------------------------------------------------------------------------------------

J. Ireland, C. A. Young, R. T. J. McAteer, C. Whelan, **R. J. Hewett**,
and P. T. Gallagher,  
*Solar Physics*, Volume 252, Issue 1, pp. 121-137, August, 2008.  
[link]
[pdf]
<a href="javascript:toggle('solphys2008a_text','solphys2008a_link');"id="solphys2008a_link">
   [show abstract]
</a>
<div id="solphys2008a_text" style="display:none;">
   Two different multiresolution analyses are used to decompose the
   structure of active-region magnetic flux into concentrations of
   different size scales. Lines separating these opposite polarity regions
   of flux at each size scale are found. These lines are used as a mask on
   a map of the magnetic field gradient to sample the local gradient
   between opposite polarity regions of given scale sizes. It is shown that
   the maximum, average, and standard deviation of the magnetic flux
   gradient for α, β, β γ, and β γ δ active-regions increase in the order
   listed, and that the order is maintained over all length scales. Since
   magnetic flux gradient is strongly linked to active-region activity,
   such as flares, this study demonstrates that, on average, the Mt. Wilson
   classification encodes the notion of activity over all length scales in
   the active-region, and not just those length scales at which the
   strongest flux gradients are found. Further, it is also shown that the
   average gradients in the field, and the average length-scale at which
   they occur, also increase in the same order. Finally, there are
   significant differences in the gradient distribution, between flaring
   and non-flaring active regions, which are maintained over all length
   scales. It is also shown that the average gradient content of
   active-regions that have large flares (GOES class “M” and above) is
   larger than that for active regions containing flares of all flare
   sizes; this difference is also maintained at all length scales. All of
   the reported results are independent of the multiresolution transform
   used. The implications for the Mt. Wilson classification of
   active-regions in relation to the multiresolution gradient content and
   flaring activity are discussed.
</div>

Multiscale Analysis of Turbulence in Active Regions Using Wavelets
------------------------------------------------------------------

**R. J. Hewett**, P. T. Gallagher, R. T. J. McAteer, C. A. Young, J.
Ireland, P. A. Conlon, and K. Maguire,  
*Solar Physics*, v. 248, no. 2, pp. 297-309, April, 2008.  
[link]
[pdf]
<a href="javascript:toggle('solphys2008b_text','solphys2008b_link');"id="solphys2008b_link">
   [show abstract]
</a>
<div id="solphys2008b_text" style="display:none;">
   Flows in the photosphere of solar active regions are turbulent in
   nature. Because magnetic fields are frozen into the plasma on the solar
   surface, magnetograms can be used to investigate the processes
   responsible for structuring active regions. Here, a continuous wavelet
   technique is developed, analyzed, and used to investigate the multiscale
   structure of an evolving active region using magnetograms obtained by
   the Michelson Doppler Imager (MDI) onboard the Solar and Heliospheric
   Observatory (SOHO). The multiscale structure was measured using a 2D
   continuous wavelet technique to extract the energy spectrum of the
   region over the time scale of 13 days. Preliminary evidence of an
   inverse cascade in active region NOAA 10488 is presented as well as a
   potential relationship between energy scaling and flare productivity.
</div>

Multifractal Properties of Evolving Active Regions
--------------------------------------------------

P. A. Conlon, P. T. Gallagher, R. T. J. McAteer, J. Ireland, C. A.
Young, P. Kestener, **R. J. Hewett**, and K. Maguire,  
*Solar Physics*, Volume 248, Issue 2, pp. 311-322, April, 2008.  
[link]
[pdf]
<a href="javascript:toggle('solphys2008c_text','solphys2008c_link');"id="solphys2008c_link">
   [show abstract]
</a>
<div id="solphys2008c_text" style="display:none;">
   Magnetohydrodynamic turbulence is thought to be responsible for
   producing complex, multiscale magnetic field distributions in solar
   active regions. Here we explore the multiscale properties of a number of
   evolving active regions using magnetograms from the Michelson Doppler
   Imager (MDI) on the Solar and Heliospheric Observatory (SOHO). The
   multifractal spectrum was obtained by using a modified box-counting
   method to study the relationship between magnetic-field multifractality
   and region evolution and activity. The initial emergence of each active
   region was found to be accompanied by characteristic changes in the
   multifractal spectrum. Specifically, the range of multifractal
   structures (D\_div) was found to increase during emergence, as was their
   significance or support (C\_div). Following this, a decrease in the
   range in multifractal structures occurred as the regions evolved to
   become large-scale, coherent structures. From the small sample
   considered, evidence was found for a direct relationship between the
   multifractal properties of the flaring regions and their flaring rate.
</div>

*IM Talking about Literacy: Instant Messaging in the Workplace*
---------------------------------------------------------------

B. Hewett and **R. J. Hewett**,  
in *Handbook of Research on Virtual Workplaces and the New Nature of Business
Practices.* Eds: Kirk St. Amant and Pavel Zemliansky. Hershey, PA, USA: IGI
Global, 2008.  
[link]
[pdf]
<a href="javascript:toggle('im2008_text','im2008_link');"id="im2008_link">
   [show abstract]
</a>
<div id="im2008_text" style="display:none;">
   This chapter discusses instant messaging (IM) as a valuable digital tool
   that has influenced business communication practices at least as much as
   e-mail. It argues that IM’s characteristics of presence awareness,
   synchronicity, hybridity, and interactivity create a unique set of
   writing and reading experiences. These functional qualities both require
   and hone high-level writing and reading skills, which are used
   powerfully in communicative multitasking. The authors believe that IM
   should be sanctioned in the workplace and that IM use should be a
   subject of focused training; to that end, they provide a practical,
   literacy-based training sequence that can be adapted to various
   settings.
</div>

2007
----

*Solar Activity Monitoring*
---------------------------

P. T. Gallagher, R. T. J. McAteer, C. A. Young, J. Ireland, **R. J.
Hewett**, and P. A. Conlon,  
in *Space Weather: Research Towards Applications in Europe.* Ed: Jean
Lilensten. Dordrecht, The Netherlands:  
Springer, 2007.  
[link]
[pdf]
