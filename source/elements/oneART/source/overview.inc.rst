.. SPDX-FileCopyrightText: 2019-2020 Intel Corporation
..
.. SPDX-License-Identifier: CC-BY-4.0

Ray Tracing defines a set of ray tracing and high-fidelity rendering
and computation routines for use in a wide variety of 3D graphics uses
including, film and television photorealistic visual effects and
animation rendering, scientific visualization, high-performance
computing computations, gaming, and more. Ray Tracing is designed to allow
cooperative execution on a wide variety of computational devices:
CPUs, GPUs, FPGAs, and other accelerators, termed “XPU”
computation. The functionality is subdivided into several domains:
geometric ray tracing computations, volumetric computation and
rendering, path guided ray tracing, image denoising, and an integrated
rendering infrastructure and API utilizing all the individual kernel
capabilities integrated into a highly capable, easy to use rendering
engine.

The individual components and their APIs are described.  Other design
considerations and related components that are not necessarily part of
the Ray Tracing specification but that are worth mentioning
will be discussed in the appendix.
