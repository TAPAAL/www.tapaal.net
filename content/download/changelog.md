---
title: "Changelog"
date: 2019-05-28T14:45:55+02:00
draft: false
---

# Changelog

**4.0.1 (2025-08-07):**

  * Minor fixes in TAPAAL GUI (opening files, redu/undo, generation of place tranistion/names and fixes to version check)

**4.0.0 (2025-06-25):**

  * Support for colored net editing, verification and unfolding/simulation
  * Support for stochastic timed-arc Petri nets and statistical model checking (SMC)
  * Support for verification of LTL and HyperLTL queries
  * New search feature for locating places/transitions by their names, also in the query dialog
  * Redisigned batch processing dialog and support for passing engine options directly in the command line
  * Numerous GUI improvements (e.g. quick zoom) and bug fixes
  * Improved performance and bug fixes in the verifypn and verifydtapn engines
    
**3.9.5 (2023-02-24):**

   * Fixing a bug with zooming when changing tabs
   * Fixing issues with boundeness check and with running some of the example nets
   * Updated verifytapn (continuous time) verification engine
   
**3.9.4 (2023-01-24):**

   * Fixing a bug for GUI reporting conclusive results for CTL and LTL model checking where there were not enough tokens.
   * An updated untimed engine verifypn which fixes the reporting of statistics for CTL model checking.

**3.9.3 (2022-10-24):**
   
   * Numerous bug fixes including passing of inclusion places to the continuous engine, fixes to the query dialog, copying of elements with environmental transitions, remembering of the last open file location, trace generation for LTL queries.
   * An updated untimed engine verifypn which fixes trace generation issues when structural reduction rules are applied.


**3.9.2 (2022-01-31):**
  
  * Fixes problem with transition name highlighting, simulation and over/under-approximation

**3.9.1 (2021-11-23):**
  
  * Numerous bug fixes
  * Improved export to tikz
  * Rearranged example nets with a few new nets
  * New versions of all three verification engines
  

**3.9.0 (2021-10-18):**
  
  * New GUI support for the creation of LTL queries, and
  * dnew LTL untimed engine as part of verifypn that also supports partial order reduction.
 

**3.8.1 (2021-04-10):**
  
  * Further improved performance of untimed verifypn engine
  * Numberous bug fixes 

**3.8.0 (2021-04-06):**
  
  * Improved performance of untimed verifypn engine
  * The GUI can now show reduced net in the editor
  * Numberous bug fixes and smaller GUI improvements

**3.7.1 (2020-11-01):**
  
  * Bug fixes for the 3.7 series
  * Fix in the verifydtapn engine that provided wrong answers for the AF queries
  * New compilation of verifypn engine

**3.7.0 (2020-09-20):**

  * Refactoring of a a large part of the GUI
  * Support for drawing game nets together with engine suport
  * Addition of lens allowing to project on timed/untimed nets and game/non-game nets
  * Quick drawing of nets when pressing ctrl (in arc-drawing mode)

**3.6.1 (2020-03-18):**

  * Highlighted constants in editor now blink
  * Save and load paths are not remembered separately
  * Fixed integration with UPPAAL verifyta engine
  * Loading of large nets is now twice as fast
  * On linux you can start tapaal with a net as argument, on mac the icon is now dropable.
  * Numerous other bug fixes and improvements

**3.6.0 (2019-10-21):** 

  * Automatic layout generator for a net (available in Tools)
  * Alignment of a net to the current grid size (available in View)
  * Numerous bug fixes

**3.5.1 (2019-04-23):**

  * Bugfixes

**3.5.0 (2019-03-18):**

  * Intervals on arcs can now be moved and placed arbitrarily
  * TAPAAL model files now end with .tapn
  * Removal of multiple places at the same time
  * Soundness check in batch processing
  * Easier sharing of places/transitions across components
  * Improved export to tikz
  * GUI refactoring and numerous bug fixes

**3.4.3 (2018-06-29):**

  * Fixes a bug in the untimed engine for partial order reduction with inhibitor arcs.
  * Fixes a bug in the unfolding of colored Petri nets in the untimed engine.

**3.4.2 (2018-05-14):**

  * Fixes issues with PNML and XML query export of nets,
  * fixes a net composition with constants on weighted arcs,
  * structural transition statistics now includes the rules A to I,
  * fixes an uncought exception when renaming transitions to an invalid name, and
  * is distributed with the untimed engine verifypn 3.0.0 contains a general performance improvement, adds support for colored nets verification (no GUI support yet) and fixes a number of bugs for nets with inhibitors arcs, arithmetic exppressions and other small issues.
  
**3.4.1 (2018-05-03):**

  * launching TAPAAL GUI on Mac Os X with Java 9,
  * conversion of Reachability to CTL queires in the query creation dialog,
  * fixes in evaluating arithmetical expressions and nested deadlock queries in the untimed verifypn engine for P/T nets.

**3.4.0 (2018-01-24):**

  * Partial order reduction to the verifydtapn engine and GUI support.
  * Support for timed-safety-games to the engine (no GUI support yet).
  * Refactoring of verifydtapn engine and all around for performance improvement (including new successor generator).
  * Numerous improvements for the untimed verifypn engine (including structural reductions for CTL and advanced query simplification algorithms).

**3.3.0 (2017-10-05):**

  * new CTL query creation dialog when modelling untimed nets
  * new CTL untimed verification engine verifypn
  * rapid drawing of nets - when holding down ctlr/cmd while creating a place/transition, continue clicking and the GUI will alternate in creating places and transitions while connecting them by arcs
  * the view menu now has the option to display tokens as dots when they are of age 0
  * numerous bug fixes and minor GUI improvements
  * 64 bit engines for windows users.

**3.2.1 (2016-09-19):**

  * numerous bug fixes in the GUI
  * improved implementation of the verifypn engine (includes CTL engine too but with no GUI support for now).

**3.2.0 (2015-11-27):**

  * the possibility to hide/show place and transition names,
  * creation of shared places and transitions directly from the context menu,
  * improved simulator that allows to setup time delays using a slider,
  * new memory compression technique (PTrie) in the engine for workflow analysis,
  * possibility to import XML queries for untimed nets from MCC-15 competition, and
  * numerous bug fixes.
 

**3.1.3 (2014-12-02):**

  * bug fixes in the workflow analysis and query creating dialog,
  * allows to execute 0 time unit delays in the simulator, and
  * improves compatibility with the most recent UPPAAL verification engine.
 

**3.1.2 (2014-08-28):**

  * bug fixes in the untimed and discrete verification engines
  * small GUI improvements in the simulator
  * fixes a bug in the query dialog that allowed to use darts in cases where it should be disabled
  * improved export/import of traces in a new XML format
 

**3.1.1 (2014-07-15):**

  * bug fixes in the untimed and discrete verification engines
  * small bug fixes in the GUI
  * PNML loading for nets with fractional x/y-coordinates
  * overrride of queries in batch processing for deadlock check
  * displays place-bound statistics for the discrete engine verifydtapn.
 

**3.1.0 (2014-06-22):**

  * PNML import/export is now available within TAPAAL GUI.
  * Over-/under-approximation of the intervals in the net.
  * Optimized workflow engine, in particular for strong soundness check.
  * New untimed structural reductions in verifyPN engine.
  * Possibility to define general arithmetic queries over the number of tokens in places (in the manual edit mode).
  * Fastes trace option added to the query dialog for the discrete-time engine.
  * Place-bound statistics of a search added for the untimed verifyPN engine.
  * Improved export of the net as a latex (tikz) file.

**3.0.0 (2014-02-26):**

  * GUI and verification support for timed workflow analysis (available under Tool/Workflow analysis) that allow to check for soundness and strong soundness of workflow nets and computing the shortest and longest execution times.
  * An untimed verification engine verifypn.
  * A new optimized broadcast translation to UPPAAL timed automata, supporting all the new features like weighted arcs and urgent transitions, and providing performace optimizations for nets containing untimed places.
 

**2.4.3 (2014-01-26):**

  * Fix in the engine verifydtapn that now corrently generates loop-traces for EG/AF queries even with Time Darts turned on.
 

**2.4.2 (2013-12-19):**

  * explanation for verification results in batch processing and correction of PTrie and Dart options for the verifydtapn engine
  * editor improvements for urgent transitions and shared places/transitions
  * problem with UPPAAL translations for models with zero tokens and zero extra tokens
  * deadlock reporting problem in simulator
  * loading invalid XML files
  * problem with removing orphan transitions that have inhibitor arcs
  * "some trace" option is now remembered
  * undo/redo of urgency flag
  * fix for boundedness check with verifydtapn engine
  * a few other bug fixes.
 

**2.4.1 (2013-09-25):**

  *a problem with loading verifyta.exe file (UPPAAL engine) on some windows installations running Java 6,
  *a bug in simulator when used with urgent transitions,
corrects the interpretation of verification results as some are actually valid also for the continuous semantics, and
  *propertly terminates processes run via the batch processing dialog.
 

**2.4.0 (2013-09-10):**

  * adds the possibility to model urgent transitions (enabled urgent transition disables time passing),
  * adds deadlock as one of a possible propositions in the query dialog (a marking is a deadlock if after any delay no transition gets ever enabled),
  * improves the simulator by adding a random automated simulator and allowing to export/import traces,
  * fixes a number of bugs and contains some GUI improvements, and
  * makes performance improvements in the discrete-time engine verifydtapn.
 

**2.3.0 (2013-04-30):**

  * supports Java 7 (and Java 6),
  * a considerably improved discrete verification engine verifydtapn 2.0 which includes semi-symbolic optimization called timed-darts and memory optimization option PTrie,
  * a brand new simulator that shows the currently enabled transitions (red ones) and future-enabled transitions (blue ones),
  * supports native file open/save dialogs,
  * contains numerous GUI improvements (constant highlight, deadlock information in trace simulation),
  * and fixes a number of bugs.
 

**2.2.1 (2012-12-05):**

  * A number of bug fixes in the discrete verification engine verifydtapn.
 
**2.2 (2012-10-22):**

  * A major upgrade of the tool featuring a new open source engine for closed timed-arc Petri nets. The main new features are
  * a new TAPAAL engine called verifydtapn for discrete verification of closed nets
  * updated TAPAAL engine verifytapn transition statistics that shows how many times transitions were enabled during the search
  * support for weighted arcs in the editor, simulator and the new engine
  * fully adjustable workspace that can be saved in preferences new shortcuts, namely the arrows that can be used both in editor and simulator (e.g. in editor  arrows left/right can increase/decrease constant values when highlighted and ctrl-M runs the verification of the currently selected query)
  * number of other GUI improvements and bug-fixes.
 

**2.1.3 (2012-10-16):**

   * A maintenance release fixing some minor problems in the editor when multiple objects were selected and when deleting places. It also fixes a problem in a simulator where arrows used in the delay field affected also the current position in the trace.
 

**2.1.2 (2012-09-30):**

  * A maintenance release fixing a few smaller bugs in the GUI as well as the interpretation of the verification answers for EG and AF queries.
 

**2.1.1 (2012-07-22):**

A maintenance release fixing several bugs and
  * improving the speed of loading large models and moving/sorting in the component list,
  * introducing a new update notification dialog,
  * fixing a rare memory leak in the TAPAAL engine verifytapn,
  * possibility to change the values of constants using the arrows left/right,
  * user preferences are now relative to the version of TAPAAL,
  * tool tips can be disabled,
  * query dialog allows to create any query and suggests automatically the most suitable verification engine, and
  * it is now possible to move in the error trace using the arrows up/down while the arrows left/right change the currently displayed component.
 

**2.1 (2012-03-17):**

  * A major release with several new features and GUI improvements.
  * A new version of TAPAAL engine that allows to use discrete inclusion technique even for queries that are now upward closed.
  * Numerous GUI improvements including a fully resizable panels, possibility for different workspace configurations for showing/hiding the interval [0,inf), and more.
  * During the verification process there is now displayed a timer.
  * Simulator now displays a clickable list of enabled transitions in all active components.
  * New engine selection dialog provides an overview of the configured engines and the settings are remembered in preferences.
  * Improved batch processing dialog with a better layout and the possibility to individually select verification engines.
  * Sorting of components shared places/transitions, queries and constants in the editor panels.
  * Improved query dialog with simplified/advanced view.
  * New net statistics tool.
  * New hot key assignments including command-modification for Mac users.
  * When a transition is select in the editor window, it can be now rotated using the mouse wheel; if a place is selected the wheel changes the number of tokens in the place.
  * Improved installation options, including an .exe launcher for windows users.
Several bug fixes.
 

**2.0.2 (2011-10-14):**

A maintenance release that fixes a number of bugs, one of them connected to slow verification in case of the presence of orphan transitions (no input and no output arcs) and it fixes some rare issues during the saving of a net. The release also improves the layout of the query dialog and several other dialogs and a new example of train level crossing has been added to File/Example net.
 

**2.0.1 (2011-08-22):**

Several bugfixes introduced in 2.0.0, one of them related to boundedness checking problem in the TAPAAL engine. Highly recommended update for all TAPAAL users.

**2.0 (2011-06-30):**

  * TAPAAL engine (both 32 and 64 bit version) with symmetry reduction, concrete trace generation, discrete inclusion, heuristic search
  * Component-based design editor with shared places and transitions
  * Flexible batch processing dialog
  * Numerous GUI improvements (view/hide of panels, updated query editor, improved verification statistics, ...)


**1.4.3 (2011-06-16):**

  * Fixes bugs (#769875, #769881, #781502)

**1.4.2 (2011-04-12):**

  * Fixes bugs with boundness checking (#737485, #750190)

**1.4.1 (2011-03-10):**

  * Bug fix release, fixes a number of bugs introduced in the 1.4 release

**1.4 (2011-01-19):**

  * New feature: timed inhibitor arcs
  * Completely new query creation dialog
  * New features: option to model and verify untimed Petri nets (mainly for educational purposes)
  * Several visual improvements
  * Bug fixes
  * Deals with the new licensing policy of UPPAAL

**1.3 (2011-01-19):**

  * New features: parameterized nets, better GUI for query and constant editting, optimization of the number of extra tokens in case the net is bounded, automatic update notification, export to tikz.
  * A new example of a web-server.
  * A number of bux fixes.

**1.2 (2009-08-05):**

  * Included demo net
  * Multiple bugfixes

**1.1 (2009-04-21):**

  * Boundedness checking
  * Visualization of untimed traces for the verification of liveness properties.

**1.0 (2009-08-05):**

  * Added query to sidebar
  * Restructured simulation to sidebar
  * Multiple bugfixes

**0.8 beta:**

  * First Public Release
  * Graphical Query Designer

**2008-08-22:**

  * Development of TAPAAL started The tool was codenamed TAPN
