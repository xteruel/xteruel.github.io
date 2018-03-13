---
layout: talk
people: "Xavier Teruel"
title: "OmpSs demos at Supercomputing 2017"
short: "OmpSs demos at SC 2017"
venue: "Colorado Convention Center"
place: "Denver, COLORADO" 
info: ""
event: 2017-11-14
time1: 11:00
close:
time2:
tags: []
category: []
comments: true
---

Two short *demos* at the exhibition center showing the basic concepts of the
OmpSs programming model. See you at the BSC booth: 1975.

> * Tuesday: November 14th, 11:00 am at BSC booth
> * Thursday: November 16th, 11:00 am at BSC booth

OmpSs is completely developed at BSC and we use it as a forerunner for OpenMP.
Like OpenMP, it is based on compiler directives. It is the base platform where
we have developed OpenMP tasking, support for dependences, priorities, task
reductions, and it also includes support for heterogeneous devices.

We will introduce the OmpSs fundamentals related to task-based parallelism
for the SMP cores and then quickly move to the support for heterogeneous
devices. OmpSs allows to leverage existing OpenCL and CUDA kernels without the
burden to have to deal with data copies to/from the devices. Data copies are
just triggered automatically by the OmpSs runtime, based on the task dependence
annotations.

