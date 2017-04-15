---
layout: post
kind: teaching
short: "PACT 2016"
title: "Heterogeneous Parallel Programming with OmpSs"
description: "Heterogeneous Parallel Programming with OmpSs"
date: 2016-07-15
venue: Technion University. Haifa, ISRAEL
event: 2016-09-15
speakers: "Xavier Martorell & Xavier Teruel"
tags: [OmpSs, CUDA, FPGAs]
comments: true
share: true
---

### Contents

This tutorial will show the OmpSs Programming Model. It will be based on both
teaching and laboratory sessions. OmpSs is a programming model developed at BSC
that we use as a forerunner for OpenMP. Like OpenMP, it is based on compiler
directives. It is the base platform where we have developed OpenMP tasking,
support for dependences, priorities, task reductions, and it also includes
support for heterogeneous devices.

We will introduce the OmpSs basic concepts related to task-based parallelism
for the SMP cores and then quickly move to the support for heterogeneous
devices. OmpSs allows to leverage existing OpenCL and CUDA kernels without the
burden to have to deal with data copies to/from the devices. Data copies are
just triggered automatically by the OmpSs runtime, based on the task dependence
annotations.

OmpSs is currently being extended for FPGA devices, in the context of the AXIOM
European Project. We will also show how the same directives are being used to
outline code that can be compiled and run on FPGA devices.

The tutorial will include two laboratory sessions. We will provide student
accounts to attendees in our Minotauro machine (Intel-based with NVidia GPUs),
and several exercises will be provided to be completed online (cholesky, matrix
multiplication, nbody, 3d-stencil, merge-sort, histogram...), and learn better
the details of the OmpSs support for both the SMP and heterogeneous
architectures.

### Agenda

 * Session 1. Introduction to OmpSs (8.00 - 10:00)
   * OmpSs tasking (fundamentals of OmpSs)
   * Task dependences (execution model)
   * Additional concurrent, commutative clauses
   * Development environment: Mercurium compiler and Nanos++
   * Hands-on on simple benchmarks: how to compile and execute applications
   
 * Session 2. OmpSs support for heterogeneous architectures (10:30 - 12:15)
   * OmpSs target extensions
   * Automatic data transfers, software cache
   * Leveraging CUDA and OpenCL kernels
   
 * Session 3. Hands-on (13:50 - 15:35)
   * Parallelizing applications on heterogeneous architectures with OmpSs
   * Cholesky, matrix multiplication, nbody, 3d-stencil, merge-sort, histogram...
  
 * Session 4. FPGA support in OmpSs (15:50 - 17:00)
   * Exploiting parallelism on FPGA devices
   * Integrating the development environment with support for FPGAs

### External references


