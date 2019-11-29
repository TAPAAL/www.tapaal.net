---
title: "Introduction"
date: 2019-05-28T14:45:55+02:00
draft: false
menu: "main"
weight: 1
---
# TAPAAL: Tool for Verification of Timed-Arc Petri Nets

<img style="float:right;margin-left:1em" src="/tapaal-frontpageimage.png"/>

**TAPAAL** is a tool for

  * modelling, simulation and verification of
  * **T**imed-**A**rc **P**etri nets
  * developed at Department of Computer Science at **AAL**borg University in Denmark
  * and available for Linux, Windows and Mac OS X platforms.

Timed-Arc Petri Net (TAPN) is a time extension of the classical [Petri net model](http://en.wikipedia.org/wiki/Petri_net) (a commonly used graphical model of distributed computations introduced by [Carl Adam Petri](http://en.wikipedia.org/wiki/Carl_Adam_Petri) in his disseration in 1962). The time extension we consider allows for explicit treatment of real-time, which is associated with the tokens in the net (each tokens has its own age) and arcs from places to transitions are labelled by time intervals that restrict the age of tokens that can be used in order to fire the respective transition. In TAPAAL tool a furter extension of this model with age invariants, urgent transitions, transport arcs (which are more expressive than for example previously considered read-arcs) and with inhibitor arcs is implemented.

The TAPAAL tool offers a graphical editor for drawing TAPN models, simulator for experimenting with the designed nets and a verification environment that automatically answers logical queries formulated in a subset of [CTL logic](http://en.wikipedia.org/wiki/Computational_tree_logic) (essentially EF, EG, AF, AG formulae without nesting). It also allows the user to check whether a given net is k-bounded for a given number k. The newest version of TAPAAL is now equipped with three open source verification engines distributed together with TAPAAL (for continuous time semantics, discrete time semantics and a new efficient engine for the verification of untimed nets). Optionally, the user can automatically translate TAPAAL models into [UPPAAL](http://www.uppaal.com/) and rely on the UPPAAL verification engine.