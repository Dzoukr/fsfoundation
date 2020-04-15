---
layout: default
title: Guide - Math and Statistics Programming with F# | The F# Software Foundation
headline: Guide - Math and Statistics Programming with F#
redirect_from: "/math/index.html"
---

## Resources for Math and Statistics

* auto-gen TOC:
{:toc}

<div class="jumbotron visible-lg calloutBox" id="how-to-add-testimonial"> 
    <p>This guide includes resources related to math and statistics programming with F#. To contribute to this guide <a href="https://github.com/fsharp/fsfoundation/edit/gh-pages/guides/math-and-statistics/index.md">edit this page</a> and send a pull request.</p>
    <hr />
    <p>Note that the resources listed below are for educational purposes related to the F# programming language. The F# Software Foundation does not endorse or recommend any commercial products, processes, or services. Therefore, mention of commercial products, processes, or services should not be construed as an endorsement or recommendation.</p>
</div>              


### Open-source libraries

 * [SciSharp Stack](https://scisharp.github.io/SciSharp/) - A .NET based Open Source Ecosystem for Data Science, Machine Learning and AI.

   SciSharp provides ports and bindings to cutting edge Machine Learning frameworks like TensorFlow, Keras, PyTorch, Numpy and many more in .NET Core. Since the APIs of the ported libraries are so similar to the originals you can easily re-use all existing resources, documentation and community solutions to common problems in C# or F# without much effort.

   License: Various, mostly Apache 2.0 or MIT
   
 * [Math.NET Numerics](http://numerics.mathdotnet.com/) - provides 
   a large collection of algorithms needed in science and engineering, including linear algebra, 
   special functions, statistics, probability models, interpolation and FFTs. 

   In addition to the core .NET package, Numerics specifically supports F# 3.0 with idiomatic extension modules and 
   maintains mathematical data structures like BigRational that originated in the F# PowerPack. 
   If a performance boost is needed, the managed-code provider backing its linear algebra routines 
   and decompositions can be exchanged with wrappers for optimized native implementations such as 
   Intel MKL. Supports Mono and .NET 4.0 on Linux, Mac and Windows. The portable version also SL5 
   and .NET for Windows Store apps.

   License: MIT/X11
   
 * [DiffSharp](http://diffsharp.github.io/DiffSharp/) - An automatic 
   differentiation (AD) library for exact and efficient calculation of derivatives. Also includes symbolic and numerical differentiation.

   AD allows exact and efficient calculation of derivatives, by systematically invoking the chain rule of calculus at the elementary operator level during program execution. AD is different from numerical differentiation, which is prone to truncation and round-off errors, and symbolic differentiation, which suffers from expression swell and cannot handle algorithmic control flow.

   Using the DiffSharp library, derivative calculations (gradients, Hessians, Jacobians, directional derivatives, and matrix-free Hessian- and Jacobian-vector products) can be incorporated with minimal change into existing algorithms.
   
   License: BSD 2-Clause

 * [FsAlg](http://gbaydin.github.io/FsAlg/) - A lightweight linear algebra library that supports generic types.

   The library provides generic Vector and Matrix types that support most of the commonly used linear algebra operations, including matrix–vector operations, matrix inverse, determinants, eigenvalues, LU and QR decompositions. Its intended use is to enable writing generic linear algebra code with custom numeric types. It can also be used as a lightweight library for prototyping and scripting with primitive floating point types.

   License: BSD

### Commercial libraries

 * [Alea GPU](https://developer.nvidia.com/alea-gpu) - a framework for 
   developing GPU-accelerated algorithms in F# on .NET and Mono.

   Utilizing F# quotations and the
   LLVM compiler it is able to compile GPU kernels on-the-fly and schedule them on one or 
   more nVidia GPU's. Advanced GPU features such as textures and shared memory are
   supported. Available from [Quantalea](http://www.quantalea.net/).

 * [ILNumerics](http://ilnumerics.net/) - an open- or closed-source library offering high-
   performance numerical algorithms as well as charting and plotting capabilities.

   The library is based on efficient, general-purpose array classes implementing vectors, matrices, and
   n-dimensional arrays. Provided algorithms include standard linear algebra transforms,
   a high-performance Fast Fourier Transform (FFT) library, and a collection of sorting 
   and machine learning algorithms. Plotting is based on OpenGL and supports both 2D and 3D
   plots. ILNumerics supports .NET 4.0 as well as Mono (recommend 2.10 or above).

   License: GPLv3 or commercial (paid) license.
   
 * [Extreme Optimization Numerical Libraries for .NET](http://www.extremeoptimization.com/) - 
   a set of three libraries focused on vector and matrix processing, 
   linear algebra methods, and statistics functions.

   The library includes a large selection of 
   standard algorithms from matrix factorization, function optimization, numerical integration, 
   K-means clustering, and PCA (principal component analysis). Options are provided to run  
   using pure managed code for portability or to utilize highly tuned native code for 
   additional performance. Extreme Optimization supports .NET 3.5 and 4.0 (2.0 version 
   available) and execution on Mono.

 * [NMath, NMath Stats](http://www.centerspace.net/products/c-sharp-vb-net-math-library-products/) -
   a suite providing core math and statistics functions.

   NMath provides sparse- and 
   dense-matrix manipulations, FFT algorithms, and numeric algorithms such as curve-fitting, 
   integration, and differentiation. NMath Stats is built on NMath and provides statistics 
   functions such multiple linear regression, hypothesis testing, and nonnegative matrix 
   factorization. NMath and NMath Stats support .NET 4.5 and are available from 
   [CenterSpace Software](http://www.centerspace.net/).

 * [F# for Numerics](http://www.ffconsultancy.com/products/fsharp_for_numerics/) - 
   a collection of numeric algorithms including matrix operations, optimization and 
   interpolation functions, 1D and 2D FFTs, and pseudo-random number generation.

   The library uses 
   the standard F# PowerPack Matrix for compatibility. F# for Numerics supports .NET. 
   The library is available from [Flying Frog Consultancy](http://www.ffconsultancy.com/).

 * [F# for Visualization](http://www.ffconsultancy.com/products/fsharp_for_visualization/index.html) -
   a 2D and 3D vector graphics library with a native F# interface.

   The package provides interactive plotting from within Visual Studio and support for generating
   animations. F# for Visualization supports .NET. The library is
   available from [Flying Frog Consultancy](http://www.ffconsultancy.com/).

