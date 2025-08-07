---
title: "Features"
date: 2019-05-28T14:45:55+02:00
draft: false
menu: "main"
weight: 2
---
# Details about TAPAAL

The TAPAAL tool provides:

  * a graphical GUI for drawing P/T nets (with PNML import/export) and colored, stochastic timed-arc Petri nets (and games),
  * a simulator,
  * a timed workflow net analyzer,
  * extension to game setting,
  * extension to colored nets,
  * extensision to stochastic nets,
  * stand-alone efficient verifiers supporting reachability analysis, CTL, LTL and HyperLTL logics,
  * a verification engine performing statistical model checking, and
  * a translation module using the UPPAAL engine at the back end.

The standard model of timed-arc Petri nets is extended with:

  * component-based design,
  * age invariants,
  * urgent transitions,
  * transport arcs, and
  * inhibitor arcs.

This extended model offers more expressive power than the standard timed-arc Petri net model [1,2,8] and such extensions are very convenient for modelling purposes. Invariants allow to model correctly hard-deadlines and transport arcs are suitable for describing for example workflow processes as with this extension a precise tracking of age of a token is possible throughout the computation of the net. The user is allowed to verify even unbounded nets. In this case the tool provides a suitable underapproximation technique as well as an automatic check whether a designed net is bounded or not for a given number of tokens that can at most appear in the net during any computation.

To the best of our knowledge, TAPAAL is the first publicly available  and maintained tool for verification of timed-arc Petri nets. Other tools for untimed Petri nets and timed Petri nets where time features are added e.g. to transitions can be found for example [here](http://www.informatik.uni-hamburg.de/TGI/PetriNets/tools/quick.html).


## Implementation details:

The GUI of TAPAAL is based on an open source project called [PIPE](http://pipe2.sourceforge.net/) and extends PIPE version 2.5 with the extra features for modelling of timed-arc Petri nets. It is implemented in Java. Java JRE 11.0 or higher is required in order to run the GUI. It is released under the [Open Software Licence 3.0](http://www.opensource.org/licenses/osl-3.0.php).

## Literature:

To cite TAPAAL, please, use the bibtex item below:

<blockquote style="margin-bottom:0;margin-top:0;">
<p style="font-family: TrebuchetMS, Arial, sans-serif; font-size: 12.92px; text-align: justify; " class="bodytext"><a name="DJJJMS:TACAS:12">@inproceedings{DJJJMS:TACAS:12,<br>&nbsp; author	={A. David and L. Jacobsen and M. Jacobsen and K.Y. J{\o}rgensen and M.H. M{\o}ller and J. Srba},<br>&nbsp;&nbsp; title	={{TAPAAL 2.0:} Integrated Development Environment for Timed-Arc {P}etri Nets},<br>&nbsp;&nbsp; booktitle	={Proceedings of the 18th International Conference on Tools and Algorithms for the Construction and Analysis of Systems ({TACAS}'12)},<br>&nbsp;&nbsp; year	={2012},<br>&nbsp;&nbsp; series	={LNCS},<br>&nbsp;&nbsp; volume	={7214},<br>&nbsp;&nbsp; publisher	={Springer-Verlag},<br>&nbsp; &nbsp;pages	={492--497},<br>}<br></a></p>
</blockoute>

 
