---
title: "Features"
date: 2019-05-28T14:45:55+02:00
draft: false
menu: "main"
weight: 2
---
# Details about TAPAAL

The TAPAAL tool provides:

  * a graphical GUI for drawing P/T nets (with PNML import/export) and extended timed-arc Petri nets,
  * a simulator,
  * a timed workflow net analyzer,
  * stand-alone efficient verifiers, and
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

The TAPN model was first used in

>[1] T. Bolognesi and F. Lucidi and S. Trigila: From Timed Petri Nets to Timed LOTOS published in Proceedings of the IFIP WG 6.1 Tenth International Symposium >on Protocol Specification, Testing and Verification in 1990 by North-Holland, Amsterdam, pages 1-14,

and

>[2] H.M. Hanisch: Analysis of Place/Transition Nets with Timed-Arcs and its Application to Batch Process Control published in Proceedings of the 14th >International Conference on Application and Theory of Petri Nets (ICATPN'93) in 1993, LNCS volume 691, pages 282-299, 1993.

A recent overview of different timed extensions of Petri nets and automata is available in

>[3] J. Srba: Comparing the Expressiveness of Timed Automata and Timed Extensions of Petri Nets published in Proceedings of 6th International Conference on >Formal Modelling and Analysis of Timed Systems (FORMATS'08), pages 15-32, volume 5215 of LNCS, Springer-Verlag, 2008.

A translation from 1-safe TAPN to networks of timed automata was suggested in

>[4] J. Srba: Timed-Arc Petri Nets vs. Networks of Timed Automata  published in Proceedings of 26th International Conference on Application and Theory of Petri >Nets (ICATPN'05), pages 385-402, volume 3536 of LNCS, Springer-Verlag, 2005

and it was later extended to bounded nets in

>[5] P. Bouyer, S. Haddad and P.-A. Reynier: Timed Petri nets and timed automata: On the discriminating power of zeno sequences published in Information and Computation, volume 206:1, 2008, pages 73-107.

Both [4] and [5] suggest the use of read/test-arcs because it adds a descriptive power to the nets. In TAPAAL tool even more general transport arcs are implemented and they allow to model read/test-arcs in a straightforward manner.

To cite TAPAAL, please, use the bibtex item below:

<blockquote style="margin-bottom:0;margin-top:0;">
<p style="font-family: TrebuchetMS, Arial, sans-serif; font-size: 12.92px; text-align: justify; " class="bodytext"><a name="DJJJMS:TACAS:12">@inproceedings{DJJJMS:TACAS:12,<br>&nbsp; author	={A. David and L. Jacobsen and M. Jacobsen and K.Y. J{\o}rgensen and M.H. M{\o}ller and J. Srba},<br>&nbsp;&nbsp; title	={{TAPAAL 2.0:} Integrated Development Environment for Timed-Arc {P}etri Nets},<br>&nbsp;&nbsp; booktitle	={Proceedings of the 18th International Conference on Tools and Algorithms for the Construction and Analysis of Systems ({TACAS}'12)},<br>&nbsp;&nbsp; year	={2012},<br>&nbsp;&nbsp; series	={LNCS},<br>&nbsp;&nbsp; volume	={7214},<br>&nbsp;&nbsp; publisher	={Springer-Verlag},<br>&nbsp; &nbsp;pages	={492--497},<br>}<br></a></p>
</blockoute>
 
