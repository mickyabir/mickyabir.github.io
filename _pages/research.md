---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

IMPL
======
**IMP** + **L**ists, or **IMPL**, is an imperative programming language based on the **IMP** programming language, with the addition of Lists over Natural numbers. In this project, we design and [implement](https://github.com/mickyabir/IMPL) the continuation-style semantics of **IMPL** using [Maude](http://maude.cs.illinois.edu/w/index.php/The_Maude_System). With the correct-by-construction executable semantics at hand, we create a prover for **IMPL** programs using the constructor-based reachability logic prover and study the proof methodology of such proofs. This tool is currently used as a teaching tool in CS 476 at UIUC.

[_Continuation Semantics and Program Verification for the IMPL Language_](https://courses.engr.illinois.edu/cs476/sp2020/readings/abir-meseguer-impl-semantics.pdf), Draft

Closing the Gap in the LLVM Backend of K
======
[M.S. Thesis](http://mickyabir.com/files/ms-thesis.pdf). Abstract: "In this thesis, we further develop part of the K framework, a framework for specifying and executing the formal semantics of languages. We dive into the LLVM backend, one of the engines for concrete execution, and implement key functionality that is present in the other concrete execution engine. We then add a new interface that is unique to the LLVM backend, making this backend diverge from the other backend. Finally, with the backend caught up and divergent, we implement and evaluate pattern matching optimization strategies."

Raincoat and DNP3 on POX
======
B.S. Thesis. Abstract: "Software-defined networking created a new level of control over networking architectures, though SDN complexity introduced new security risks. When SDN is used in power grids, these flaws can become devastating. This thesis continues efforts to secure SDN architectures in power grids by implementing Raincoat, a randomization algorithm for data obfuscation on power grid networks. A new parser for DNP3, the protocol used for communicating power grid data, is implemented."
