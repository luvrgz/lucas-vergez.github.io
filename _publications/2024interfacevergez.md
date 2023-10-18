---
title: "Interface-based search and automatic reassembly of CAD models for database expansion and model reuse"
collection: publications
permalink: /publications/2024interfacevergez
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-01-02
venue: 'Computer-Aided Design Journal'
paperurl: ''
citation: 'VERGEZ, Lucas, POLETTE, Arnaud, et PERNOT, Jean-Philippe. Interface-based search and automatic reassembly of CAD models for database expansion and model reuse.'
---

This last paper has been accepted the 8th oh October 2023.

This paper introduces a new framework for reassembling CAD models of mechanical parts. The generated CAD assemblies are well-
constrained, with collision-free parts, and they are ready-to-use for downstream applications. First, input dead CAD models candidate
for the reassembly are sorted following a part-by-part interface-based identification algorithm that is capable of characterizing each
part according to the assembly slots and interfaces it offers. The slots are then hashed, and the resulting keys are used for fast search of
parts in the database. Thus, the parts that can be assembled are quickly identified, and their assembly can be considered according to
various scenarios. To support the reassembly steps and satisfy the constraints associated with the specified interfaces, a collision-free
kinematic constraint solver is also proposed. During the reassembly steps, the geometry of the slots can also be automatically modified
to adjust their dimensions, in order to ensure a perfect fit and to avoid interference at the level of the interfaces. The resulting database
can also be further expanded while modifying the relative positions/orientations of the assembled parts. The approach is illustrated
on several test cases covering different exploitation scenarios, ranging from simple model reuse to database expansion for machine
learning-based applications. Such an automatic reassembly process is particularly innovative, and it clearly paves the way for smart
assembly procedures.

![alt text](.\images\overall.png "Overall method of the paper")