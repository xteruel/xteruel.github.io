---
layout: project
title: OpenMP Project
categories: [openmp]
---

The parallel programming model group has been working with the OpenMP
specification since the creation of BSC in 2005. First becoming part of the
cOMPunity group (since 1998) and later on as an auxiliary member (since 2013).

Many of the ideas from OmpSs and StarSs have been introduced into the OpenMP
specification. Starting from the version 3.0, released on May 2008, OpenMP
included the support for asynchronous tasks. BSC provided the reference
implementation using the Nanos4 run-time library and the Mercurium C/C++
source-to-source compiler. This reference implementation was used to measure
the benefits that tasks can provide to the programming model. Later, on its
version 4.0 released on July 2013, OpenMP introduced tasks dependences, which
allow fine-grain synchronization between tasks and that were included in
StarSs/OmpSs as part of its main philosophy. The last 4.5 specification
(November 2015) includes the task priority clause, allowing the programmers to
provide hints to the runtime task scheduler about the importance of a task.
Currently we are working on a task reduction mechanism which will allow task to
participate in the computation of a reduction pattern.

The main goal of this research line is to serve as the technology transfer
process within the parallel programming model group. Investigate different
programming techniques which are currently at the research stage and push them
into the OpenMP specificatioy to ensure these technological developments can be
applied in real systems.

