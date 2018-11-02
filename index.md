---
layout: default
title: Home
---

## Introduction

{% if site.title == 'KF6009' %}
<p class="lead">
This module is about the theory and practice of modelling,
specification and analysis for the development of computer software. You will
be introduced to a variety of formal methods, such as state transition systems,
timed and probabilistic automata, and temporal logic. You will be encouraged to
construct, analyse and refine your own system models. In addition, you will
gain experience with state-of- the-art software engineering tools for design
and analysis.
</p>
{% elsif site.title == 'CM0604' %}
<p class="lead">
This module is designed to serve as an introduction to formal methods for
specifying, designing and reasoning about embedded systems. The module uses
state-of-the-art tools and techniques, including TLA+, UPPAAL and PRISM. It
emphasises the importance of constructing and analysing models in the early
stages of system development.
</p>
{% endif %}

<img src="assets/images/cm0604_image.png" alt="Embedded systems tools" class="img-responsive center-block"/>
Lectures are the main vehicle by which you will be introduced to fundamental
concepts and principles and for providing context and motivation. You will be
expected to prepare for lecture topics and deepen your understanding of course
material by studying course texts and technical literature. Seminars and
practical sessions support the lecture programme by providing you with
opportunities to identify defend and apply appropriate methods and tools for
specification and design. Software tools are available outside formal contact
time to enable you to explore aspects of the subject independently.

In particular the module will cover topics such as:

+ *Modelling* - variety of formal methods, e.g. state transition systems,
timed and probabilistic automata; use of abstraction; modelling of functional,
temporal and security aspects of system behaviour.
+ *Specification* – propositional, predicate and temporal logic; safety and
  liveness properties: deadlock freedom, fairness, bounded response, security.
+ *Analysis* - principles of model-checking, simulation, and static analysis
for reasoning about system behaviour.
+ *Tools* - use of tools, e.g. TLA+, Uppaal, PRISM, and evaluation of their
  outputs.
  
## Module Team

|   |    |
|---|:---|
|Module Tutor      | [David Kendall](https://davidkendall.github.io/)
|Lecturer &nbsp;  | [Alun Moon](http://computing.northumbria.ac.uk/staff/cgam1)|


## Teaching Arrangements

|   |    |
|---|:---|
**Lecture** &nbsp;| Tue 11.00-13.00 ELA 109
**Lab/Seminar**   | Fri 16.00-18.00 CIS 202

<p class="text-info">
You should attend the lecture session and the lab/seminar session every week.
</p>

## Synopsis
The aim of the module is to provide an understanding of the theory and practice
of modelling, specification and analysis in the design of computer software.

On completion of this module, students are expected to be able to:

1. Discuss the theoretical principles of various formal methods for the
   specification and design of computer software, and the algorithms and data
   structures used in their supporting tools.
1. Construct and evaluate formal models of a variety of computer systems.
1. Compose formal specifications of system properties and analyse system models
   with respect to them.
1. Identify, apply and evaluate appropriate software tools to support the
   construction and analysis of formal system models and properties.
1. Evaluate the advantages and disadvantages of the application of various
   formal methods in the development of computer software, and justify their
   use where appropriate, having regard to professional, ethical, technical and
   security issues.

## Teaching Plan

The following is a *provisional* guide to the organisation of the
module for this year. These arrangements are subject to change during the
course of the module.


| Week   | W/c   | Lecture    | Practical   |
| :----: | :---: | :--------: | :---------: |
**1** | 01 Oct &nbsp; | [Module Introduction and Overview <br/> A first TLA+ specification]({{site.baseurl}}{{site.raurl}}/A01.pdf)  <br/> *Reading:* [NRZ+14]({{site.baseurl}}{{site.raurl}}/reading/nrz+14.pdf), [HOL14]({{site.baseurl}}{{site.raurl}}/reading/hol14.pdf) <br/> *Video:* [VID01](http://lamport.azurewebsites.net/video/intro.html), [VID02](http://lamport.azurewebsites.net/video/smintla.html) | [First steps with the TLA+ Toolbox](L01.html) 
**2** | 08-Oct &nbsp; | [TLA+ : Functions]({{site.baseurl}}{{site.raurl}}/A02.pdf) <br/> *Reading:* [[LEV95]({{site.baseurl}}{{site.raurl}}/reading/lev95.pdf)] <br/> *Video:* [VID04](https://lamport.azurewebsites.net/video/video4.html), [VID05](http://lamport.azurewebsites.net/video/video5.html)| [More TLA+](L02.html)
**3** | 15-Oct &nbsp; | [TLA+ : Tuples, Strings, Records; Pluscal]({{site.baseurl}}{{site.raurl}}/A03.pdf) &nbsp; | [Pluscal, TLA+, TLC: Essential modelling techniques and invariant checking](L03.html)
**4** | 22-Oct &nbsp; | [More Pluscal; Modelling concurrent systems; Mutual exclusion]({{site.baseurl}}{{site.raurl}}/A04.pdf)  &nbsp; | [Modelling mutual exclusion: safety and deadlock](L04.html)
**5** | 29 Oct &nbsp; | [Temporal logic; Safety, liveness and fairness]({{site.baseurl}}{{site.raurl}}/A05.pdf) <br/> *Reading:* [[DAC99]({{site.baseurl}}{{site.raurl}}/reading/dac99.pdf)] [[SAC03]({{site.baseurl}}{{site.raurl}}/reading/sac03.pdf)]| [Modelling mutual exclusion: liveness](L05.html)
**6** | 05-Nov &nbsp; | [Modelling communication via message channels <br/> Inside a model-checker]({{site.baseurl}}{{site.raurl}}/A06.pdf) | [Alternating bit protocol](L06.html)
**7** | 12-Nov &nbsp; | [Modelling and analysis of security protocols.]({{site.baseurl}}{{site.raurl}}/A07.pdf)  &nbsp; | [Modelling and analysis of security protocols](L07.html) <br/> Introduction to the assignment
**8** | 19-Nov &nbsp; | [Modelling real-time systems: timed automata and timed transition systems]({{site.baseurl}}{{site.raurl}}/A08.pdf) <br/> [[Uppaal tutorial]({{site.baseurl}}{{site.raurl}}/reading/uppaal-tutorial2004.pdf)] | [Introduction to Uppaal](L08.html)
**9** | 26-Nov &nbsp; | [Networks of timed automata. Specifying real-time properties.]({{site.baseurl}}{{site.raurl}}/A09.pdf) <br/> *Reading:* [[HOL01]({{site.baseurl}}{{site.raurl}}/reading/hol01.pdf)]&nbsp; | [Modelling a box sorter](L09.html) [[Model]({{site.baseurl}}{{site.raurl}}/resources/box-sorter.xml)]
**10** | 03-Dec &nbsp; | [Uppaal language extensions and case study]({{site.baseurl}}{{site.raurl}}/A10.pdf) [[Case study resources]({{site.baseurl}}{{site.raurl}}/resources/case_study.zip)] &nbsp; | [Modelling and verifying a real-time communication protocol](L10.html) [[Model]({{site.baseurl}}{{site.raurl}}/resources/ttp.xml)]
**11** | 10-Dec &nbsp; | [Principles of automata-theoretic verification of real-time systems]({{site.baseurl}}{{site.raurl}}/A11.pdf) &nbsp; | [Synthesising a schedule](L11.html) [[Model]({{site.baseurl}}{{site.raurl}}/resources/bridge.xml)]; Assignment support
**12** | 17-Dec &nbsp; | [Introduction to probabilistic modelling]({{site.baseurl}}{{site.raurl}}/A12.pdf) &nbsp; | [Using PRISM](L12.html); Assignment support

<br/>

<p class="text-info">
In addition to the taught sessions, you are expected to undertake independent
and directed learning. This is a 20-credit module, for which the expected
student workload is 200 hours. Over the course of a 15-week semester, you
should be spending about 13 hours per week on this module.
</p>

## Assessment

Summative assessment comprises:

* a substantial exercise in specification, design and analysis in which students will be required to demonstrate both a practical ability to apply appropriate languages, techniques and tools, and also an understanding of the theoretical principles underlying their practice. This is a single assessment, contributing 100% of the
module mark.

The assessment specification will be made available to students in week 8 and will be discussed in the lab session that week. The work is due to be submitted via the elP (Blackboard) by 23.59 on Thursday 17 January 2019. Feedback and provisional marks will be provided to students by email within 20 working days of submission.

<!--<a class="btn btn-large btn-primary" href="{{site.baseurl}}{{site.raurl}}/assgn.pdf"><i class="icon-upload-alt"></i>Download Assignment Specification</a>-->

Assessment is subject to the Academic Regulations for Taught Awards. You should ensure that you are familiar with the latest regulations, particularly with regard to academic misconduct and late submission of work.

You can view the latest module evaluation document

## Recommended Reading
<p>
There is no essential text for this module. Below is a list of references to
texts and other resources that are relevant to the content of the module.
You may find many of them useful and/or interesting. In addition, you are
required to undertake some background reading about the use of formal methods
in the development of embedded and critical systems.
</p>
<ul>
<li>
Alavi, H. et al., <a href="http://patterns.projects.cs.ksu.edu/">SPEC Patterns</a>, 2005</li>
<li>
Barland, I.; Vardi, M.; Greiner, J. <a href="http://cnx.org/contents/cd5745fd-3270-46ee-9b64-6e4843b67c43@3.4/Model_Checking_Concurrent_Prog">Model Checking Concurrent
Programs</a>,
April, 2007.
</li>
<li>
Behrmann,G., David,A., and Larsen,K.
<a href="http://www.it.uu.se/research/group/darts/papers/texts/new-tutorial.pdf">A Tutorial on Uppaal</a>, Department of Computer Science, Aalborg University, Denmark, 2004
</li>
<li>
Berard, B. et al., Systems and Software Verification: Model Checking
Techniques and Tools, Springer Verlag, 2010</li>
<li>
Cooling, J.E. Software Engineering for Real-Time
Systems. Addison-Wesley, 2003.</li>
<li>
Holzmann, G., The SPIN Model Checker: Primer and Reference Manual,
Addison Wesley, 2003, ISBN 0321228626</li>
<li>Holzmann, G., <a href="{{site.baseurl}}{{site.raurl}}/reading/hol14.pdf">Mars Code</a>, Communications of the ACM, 57(2), Feb 2014
</li>
<li>Huckle, T.
<a href="ext:bugse">Collection of Software Bugs</a>, 2004</li>
<li>Huth, M., Ryan, M., <em>Logic in Computer Science: Modelling and
  Reasoning about Systems</em> 2nd edition, Cambridge University Press, 2004.
</li>
<li>Lamport, L., <a href="{{site.baseurl}}{{site.raurl}}/SpecifyingSystemsTLA+.pdf">Specifying Systems: The TLA+ Language and Tools for Hardware and Software Engineers</a>, Addison Wesley Professional, 2002</li>
<li>Lamport, L., <a href="{{site.baseurl}}{{site.raurl}}/start.pdf">The TLA+ Hyperbook</a>, 2018</li>
<li>Lamport, L., <a href="https://lamport.azurewebsites.net/tla/p-manual.pdf">A PlusCal User's Manual, P-Syntax, Version 1.8</a>, 2017 (<a href="{{site.baseurl}}{{site.raurl}}/p-manual.pdf">Local copy</a>)
</li>
<li>Lee, E. and Seshia, S., <a href="http://LeeSeshia.org">Introduction to Embedded Systems, A Cyber-Physical Systems Approach</a>, Second Edition, LeeSeshia.org, ISBN 978-1-312-42740-2, 2015. <br/>
  A free text book by Edward A. Lee and Sanjit A. Seshia that provides a modern introduction to embedded systems.
</li>
<li>Parker, D., <a href="http://www.prismmodelchecker.org/tutorial/">PRISM Tutorial</a>
</li>
<li>Vaandrager, F., <a href="http://www.cs.ru.nl/~fvaan/PV/what_is_a_good_model.html">What is a good model</a>, Unpublished note, 2010
</li>
<li>
Technical journals and conference papers, e.g. Computer Aided
Verification (CAV), Tools and Algorithms for the Construction of
Systems (TACAS)</li>
</ul>

## Other Resources

<p>
<a href="https://lamport.azurewebsites.net/tla/tla.html">
<img class="image-responsive pull-right" src="assets/images/tlaplus.png"
     alt="TLA+ Logo"    width="80" /></a>
</p>
<p>
<strong><a href="https://lamport.azurewebsites.net/tla/tla.html">TLA+</a></strong><br/>

"TLA+ (pronounced as tee ell a plus, /ˈtiː ɛl eɪ plʌs/) is a formal
specification language developed by Leslie Lamport. It is used to design,
model, document, and verify concurrent systems. TLA+ has been described as
exhaustively-testable pseudocode and blueprints for software systems; the
TLA stands for "Temporal Logic of Actions."

For design and documentation, TLA+ fulfills the same purpose as informal
technical specifications. However, TLA+ specifications are written in a formal
language of logic and mathematics, and the precision of specifications written
in this language is intended to uncover design flaws before system
implementation is underway.

Since TLA+ specifications are written in a formal language, they are amenable
to finite model checking. The model checker finds all possible system
behaviours up to some number of execution steps, and examines them for
violations of desired invariance properties such as safety and liveness. TLA+
specifications use basic set theory to define safety (bad things won't happen)
and temporal logic to define liveness (good things eventually happen).

TLA+ is also used to write machine-checked proofs of correctness both for
algorithms and mathematical theorems. The proofs are written in a declarative,
hierarchical style independent of any single theorem prover backend. Both
formal and informal structured mathematical proofs can be written in TLA+; the
language is similar to LaTeX, and tools exist to translate TLA+ specifications
to LaTeX documents.

TLA+ was introduced in 1999, following several decades of research into a
verification method for concurrent systems. A toolchain has since developed,
including an IDE and distributed model checker. The pseudocode-like language
PlusCal was created in 2009; it transpiles to TLA+ and is useful for specifying
sequential algorithms. TLA+2 was announced in 2014, expanding language support
for proof constructs. The current TLA+ reference is <a
href="https://lamport.azurewebsites.net/tla/hyperbook.html">The TLA+
Hyperbook</a> by Leslie Lamport." (adapted from <a
href="https://en.wikipedia.org/wiki/TLA%2B">Wikipedia</a>) </p> 
<ul>
<li><a href="https://tla.msr-inria.inria.fr/tlatoolbox/doc/contents.html">TLA+ Toolbox User's Guide</a></li>
<li><a href="https://lamport.azurewebsites.net/tla/summary-standalone.pdf">TLA+ Cheat Sheet</a>
(<a href="{{site.baseurl}}{{site.raurl}}/summary-standalone.pdf">Local copy</a>)</li>
<li><a href="https://lamport.azurewebsites.net/video/videos.html">TLA+ Video Course</a></li>
</ul>

<!--<p> <a href="http://spinroot.com/spin/whatispin.html">-->
<!--<img class="image-responsive pull-right"-->
<!--src="assets/images/spinlogo2_medium.gif" alt="SPIN Logo"    width="80" /></a>-->
<!--</p> <p> <strong><a-->
<!--href="http://spinroot.com/spin/whatispin.html">SPIN</a></strong><br/> "Spin is-->
<!--a popular open-source software tool, used by thousands of people worldwide,-->
<!--that can be used for the formal verification of distributed software systems.-->
<!--The tool was developed at Bell Labs in the original Unix group of the Computing-->
<!--Sciences Research Center, starting in-->
<!--1980. The software has been available freely since 1991, and continues to-->
<!--evolve to keep pace with new developments in the field. In April 2002 the-->
<!--tool was awarded the prestigious System Software Award for 2001 by the-->
<!--ACM." [<a-->
<!--href="http://awards.acm.org/award_winners/holzmann_1625680.cfm">Holzmann</a>]-->
<!--</p> <p> The main focus of this module, in weeks 1-4, is on the theory-->
<!--and practical application of this tool to the modelling and analysis of-->
<!--embedded systems. It is essential that you use the tool extensively on a-->
<!--variety of lab exercises. The tool is installed in PB Lab F1 on the Linux-->
<!--machines. It is also available free for use on your own machines -- see-->
<!--the <a href="http://spinroot.com/spin/Man/README.html">download</a>-->
<!--instructions.  </p>-->

<!--<ul>-->
<!--<li><a href="http://spinroot.com/spin/Man/3_SpinGUI.html">Getting Started with SPIN</a></li>-->
<!--<li><a href="http://spinroot.com/spin/Man/">SPIN online references</a></li>-->
<!--</ul>-->

<p>
  <a href="http://www.uppaal.org">
<img class="image-responsive pull-right" src="http://www.it.uu.se/research/group/darts/uppaal/uppaal-sim-350.png"
     alt="Uppaal Logo"    width="100" /></a>
</p>
<p>
<strong><a href="http://www.uppaal.org/">UPPAAL</a></strong><br/>

"Uppaal is an integrated tool environment for modeling, validation and
verification of real-time systems modeled as networks of timed
automata, extended with data types (bounded integers, arrays, etc.).
</p>
<p>
The tool is developed in collaboration between the Department of
Information Technology at Uppsala University, Sweden and the
Department of Computer Science at Aalborg University in Denmark."
</p>

<p>
  It is also available for <a href="http://www.uppaal.com/">commercial use</a>.
</p>

<p>
The main focus of this module, in weeks 8-11, is on the theory and
practical application of this tool to the modelling and analysis of
embedded systems. It is essential that you use the tool extensively on
a variety of lab exercises. The tool is installed on the
Linux machines in the CIS labs on the 2nd floor. It is also available free for use on your own machines.
There is a tutorial that gives a good
introduction to the theory and practice of modelling with timed
automata and analysis with the Uppaal tool.
</p>
<p>
  <a href="http://www.prismmodelchecker.org">
<img class="image-responsive pull-right" src="http://www.prismmodelchecker.org/images/ss_graph.png"
     alt="PRISM Logo"    width="100" /></a>
</p>
<p>
<strong><a href="http://www.prismmodelchecker.org/">PRISM</a></strong><br/>
"PRISM is a probabilistic model checker, a tool for formal modelling and
analysis of systems that exhibit random or probabilistic behaviour. It has been
used to analyse systems from many different application domains, including
communication and multimedia protocols, randomised distributed algorithms,
security protocols, biological systems and many others." The tool is <a
  href="http://www.prismmodelchecker.org/download.php">free to download</a>.
</p>

## Professionalism, ethics and standards


<ul>
<li>
<a href="http://www.acm.org/about-acm/acm-code-of-ethics-and-professional-conduct">ACM Code of Ethics and Professional Conduct</a>
</li>

<li>
<a href="http://www.bcs.org/server.php?show=nav.6029">BCS Code of Conduct and Good Practice</a>
</li>

<li>
<a href="http://www.ieee.org/about/corporate/governance/p7-8.html">IEEE Code of Ethics</a>
</li>

<li>
<a href="http://www.raeng.org.uk/policy/engineering-ethics/ethics">Royal academy of engineering: Engineering ethics</a>
</li>

<li>
<a href="http://cogprints.ecs.soton.ac.uk/archive/00003299/">Ehical issues in empirical studies of software engineering</a>
</li>

<li>
Hennell,M., Woodcock,J. and Woodward,M., <a href="http://www.fuji-setsu.co.jp/files/IEC61508_ldra.pdf">The Safety Integrity Levels Of IEC 61508 And A Revised Proposal</a>, Embedded Systems Show, 2006. (<a href="{{site.baseurl}}{{site.raurl}}/reading/hww06.pdf">Local copy</a>)
</li>

<li>Redmill,F., <a href="http://homepages.cs.ncl.ac.uk/felix.redmill/publications/4B.IEC%2061508%20Intro.pdf">An Introduction To The Safety Standard IEC 61508</a>, Journal of the System Safety Society, Volume 35, No. 1, 1999
</li>

<li>International Standardization Organization, <a href="https://www.iso.org/obp/ui/#iso:std:iso:26262:-1:ed-1:v1:en">ISO 26262 Road vehicles - Functional Safety</a>, 2011. (<a href="http://en.wikipedia.org/wiki/ISO_26262">Wikipedia</a>)
</li>

<li>
BS EN 50128:2011 Railway applications. Communication, signalling and
processing systems. Software for railway control and protection
systems
</li>

<li>
IEC 60880 Nuclear power plants - Instrumentation and control systems
important to safety - Software aspects for computer-based systems
performing category A functions, 2006
</li>

<li>
<a href="http://cpsr.org/">Computer Professionals for Social Responsibility</a>
</li>

</ul>

## Security

<ul>
<li>Anderson, R., <em>Security Engineering: A guide to building dependable distributed systems</em> (2nd edition), John Wiley, 2008 [<a href="{{site.baseurl}}{{site.raurl}}/reading/and08.pdf">local copy of Chapter 5: Cryptography</a>]</li>
<li> Halperin, D., Heydt-Benjamin, T.S., Ransford, B.,  Clark, S.S., Defend, B., Morgan, W., Fu, K., Kohno, T. and Maisel, W.H., <em>Pacemakers and Implantable Cardiac Defibrillators: Software Radio Attacks and Zero-Power Defenses</em>, IEEE Symposium on Security and Privacy, 129-142, May, 2008 [<a href="{{site.baseurl}}{{site.raurl}}/reading/hhr08.pdf">pdf</a>]</li>
<li> Koopman, P., <em>Embedded system security</em>, IEEE Computer, 37(7): 95-97, July 2004 [<a href="{{site.baseurl}}{{site.raurl}}/reading/koo04.pdf">pdf</a>]</li>
<li> Karl Koscher, Alexei Czeskis, Franziska Roesner, Shwetak Patel, and Tadayoshi Kohno, Stephen Checkoway, Damon McCoy, Brian Kantor, Danny Anderson, Hovav Shacham, and Stefan Savage, <em>Experimental Security Analysis of a Modern Automobile</em>, IEEE Symposium on Security and Privacy 2010, 447-462, 2010 [<a href="{{site.baseurl}}{{site.raurl}}/reading/kcr10.pdf">pdf</a>]</li>
<li> Maggi, P. and Sisto, R., <em>Using SPIN to verify security properties of cryptographic protocols</em>, Proceedings of SPIN Workshop 2002, LNCS 2318, 187-204, Springer Verlag, 2002 [<a href="{{site.baseurl}}{{site.raurl}}/reading/ms02.pdf">pdf</a>]</li>
<li> Ryan, P., Schneider, S., Goldsmith, M. and Lowe, G., <em>Modelling and analysis of security protocols: the CSP approach</em>, Addison Wesley, 2000 [<a href="{{site.baseurl}}{{site.raurl}}/reading/rsg00.pdf">pdf</a>]</li>
</ul>

