---
layout: default
title: Home
---
# Introduction


<p class="lead">
This module is designed to serve as an introduction to formal and object-oriented methods for specifying, designing and reasoning about embedded systems. The module uses state-of-the-art tools and techniques, including SPIN, UPPAAL and PRISM. It emphasises the importance of constructing and analysing models in the early stages of system development.
</p>


<img src="assets/images/cm0604_image.png" alt="Embedded systems tools" class="img-responsive center-block"/>
The main ideas are communicated in a series of 12 lectures. The laboratory sessions are used to put these ideas into practice in a variety of modelling and analysis exercises. By the end of the module, you should be able to take an informal specification of an embedded system, construct a formal model of (part of) a design and reason about the likely behaviour of the system. The understanding gained in this process can be invaluable in the implementation of a reliable system.

The principles and techniques taught in this module are used extensively in the module EN0617 Industrial Case Project.

# Module Team

|   |    |
|---|:---|
|Module Tutor      | [David Kendall](http://computing.northumbria.ac.uk/staff/cgdk2)
|Lecturer &nbsp;  | [Michael Brockway](http://computing.northumbria.ac.uk/staff/cgmb3)|


# Teaching Arrangements

|   |    |
|---|:---|
**Lecture** &nbsp;| Mon 09.00-11.00 ELA 218
**Lab/Seminar**       | Tue 11.00-13.00 PB F1

<p class="text-info">
You should attend <em>both</em> lecture sessions and the
lab/seminar session every week.
</p>

# Synopsis

The aim of the module is to provide an understanding of the theory and practice
of modelling, specification and analysis in the design of embedded systems.

On completion of this module, students will be able to:

1. Evaluate the advantages and disadvantages of the application of formal and object-oriented methods in the development of embedded systems, and justify their use where appropriate; having regard to professional, technical and security issues.
2. Construct and evaluate formal and object-oriented models of a variety of small embedded systems.
3. Compose formal specifications of system properties and analyse system models with respect to them.
4. Identify, apply and evaluate appropriate software tools to support the construction and analysis of formal and object-oriented system models and properties.

# Teaching Plan

The following is a *provisional* guide to the organisation of this part of the
module for this year. These arrangements are subject to change during the
course of the module.


| Week   | W/c   | Lecture A   | Practical   |
| :----: | :---: | :---------: | :---------: |
**1** | 18-Sep &nbsp; | [Module overview and introduction]({{site.raurl}}/A01.pdf) <br/> *Reading:* [HOL14]({{site.raurl}}/reading/hol14.pdf) | [SPIN and PROMELA]({{site.raurl}}/spinintro.pdf) [[Exercises]({{site.raurl}}/L01.pdf)]
**2** | 25-Sep &nbsp; | [Modelling and specificaton with Finite State Automata I]({{site.raurl}}/A02.pdf) | [More PROMELA]({{site.raurl}}/spinintro.pdf) [[Exercises]({{site.raurl}}/L02.pdf)]
**3** | 02-Oct &nbsp; | [Modelling and specification with Finite State Automata II]({{site.raurl}}/A03.pdf) <br/> [[Mutex model]({{site.raurl}}/resources/mutex1.pdf)] &nbsp; | [Checking liveness properties with SPIN]({{site.raurl}}/L03.pdf) <br/> [[Outline solutions 1,2]({{site.raurl}}/resources/solutions_01-02.zip)]
**4** | 09-Oct &nbsp; | [Temporal logic. Specification patterns.]({{site.raurl}}/A04.pdf) <br/> *Reading:* [[DAC99]({{site.raurl}}/reading/dac99.pdf)] [[SAC03]({{site.raurl}}/reading/sac03.pdf)] &nbsp; | [Temporal logic specification and analysis]({{site.raurl}}/L04.pdf) <br/> [[Outline solutions 3,4]({{site.raurl}}/resources/solutions_03-04.zip)]
**5** | 16-Oct &nbsp; | [Modelling and analysis of security protocols.]({{site.raurl}}/A05.pdf) [Timed automata and timed transition systems]({{site.raurl}}/A05a.pdf) <br/> [[Uppaal tutorial]({{site.raurl}}/reading/uppaal-tutorial2004.pdf)] [[LEV95]({{site.raurl}}/reading/lev95.pdf)]&nbsp; | [Introduction to Uppaal]({{site.raurl}}/L05.pdf)
**6** | 23-Oct &nbsp; | [Networks of timed automata. Specifying real-time properties.]({{site.raurl}}/A06.pdf) <br/> *Reading:* [[HOL01]({{site.raurl}}/reading/hol01.pdf)]&nbsp; | [Modelling a box sorter]({{site.raurl}}/L06.pdf) [[Model]({{site.raurl}}/resources/box-sorter.xml)]
**7** | 30-Oct &nbsp; | [Uppaal language extensions and case study]({{site.raurl}}/A07.pdf) [[Case study resources]({{site.raurl}}/resources/case_study.zip)] &nbsp; | [Modelling and verifying a real-time communication protocol]({{site.raurl}}/L07.pdf) [[Model]({{site.raurl}}/resources/ttp.xml)]
**8** | 06-Nov &nbsp; | [Principles of automata-theoretic verification of real-time systems]({{site.raurl}}/A08.pdf) &nbsp; | [Synthesising a schedule]({{site.raurl}}/L08.pdf) [[Model]({{site.raurl}}/resources/ttp.xml)]
**9** | 13-Nov &nbsp; | [Introduction to probabilistic modelling. PRISM]({{site.raurl}}/A09.pdf) &nbsp; | [Probabilistic Models Lab 1]({{site.raurl}}/L09.pdf)
**10** | 20-Nov &nbsp; | [More on PRISM]({{site.raurl}}/A10.pdf) &nbsp; | [Probabilistic Models Lab 2]({{site.raurl}}/L10.pdf)
**11** | 27-Nov &nbsp; | [Probabilistic automata]({{site.raurl}}/A11.pdf) &nbsp; |[Probabilistic Models Lab 3]({{site.raurl}}/L10.pdf)
**12** | 04_Dec &nbsp; | [Probabilistic temporal logic]({{site.raurl}}/A12.pdf) &nbsp; | [Probabilistic Models Lab 4]({{site.raurl}}/L12.pdf)

<br/>

<p class="text-info">
In addition to the taught sessions, you are expected to undertake independent
and directed learning. This is a 20-credit module, for which the expected
student workload is 200 hours. Over the course of a 15-week semester, you
should be spending about 13 hours per week on this module.
</p>

# Assessment

Summative assessment comprises:

* a substantial exercise in specification, design and analysis in which students will be required to demonstrate both a practical ability to apply appropriate languages, techniques and tools, and also an understanding of the theoretical principles underlying their practice.

The assessment specification will be made available to students in week 6 and will be discussed in the lab session that week. The work is due to be submitted via the elP (Blackboard) by 23.59 on Thursday of week 13. Feedback and provisional marks will be provided to students by email within 20 working days of submission.

<a class="btn btn-large btn-primary" href="{{site.raurl}}/assgn.pdf"><i class="icon-upload-alt"></i>Download Assignment Specification</a>

Assessment is subject to the Academic Regulations for Taught Awards. You should ensure that you are familiar with the latest regulations, particularly with regard to academic misconduct and late submission of work.

You can view the latest module evaluation document

# Recommended Reading
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
Douglass, B.P. Real-Time UML. Addison-Wesley, 1999.</li>
<li>
Douglass, B.P. Doing Hard Time. Addison-Wesley, 1999.</li>
<li>
Gomaa, H. Designing Concurrent Distributed and Real Time Applications
with UML. Addison-Wesley, 2000.</li>
<li>Harel, D.
<a href="http://www.wisdom.weizmann.ac.il/~dharel/SCANNED.PAPERS/VisualFormalisms.pdf"><em>On Visual Formalisms</em></a> and <a href="http://www.wisdom.weizmann.ac.il/~dharel/SCANNED.PAPERS/BitingTheSilverBullet.pdf"><em>Biting the Silver Bullet: Toward a Brighter Future for System Development</em></a></li>
<li>
Holzmann, G., The SPIN Model Checker: Primer and Reference Manual,
Addison Wesley, 2003, ISBN 0321228626</li>
<li>Holzmann, G., <a href="{{site.raurl}}/reading/hol14.pdf">Mars Code</a>, Communications of the ACM, 57(2), Feb 2014
</li>
<li>Huckle, T.
<a href="ext:bugse">Collection of Software Bugs</a>, 2004</li>
<li>Huth, M., Ryan, M., <em>Logic in Computer Science: Modelling and
  Reasoning about Systems</em> 2nd edition, Cambridge University Press, 2004.
</li>
<li>Lee, E. and Seshia, S., <a href="http://LeeSeshia.org">Introduction to Embedded Systems, A Cyber-Physical Systems Approach</a>, Second Edition, LeeSeshia.org, ISBN 978-1-312-42740-2, 2015. <br/>
  A free text book by Edward A. Lee and Sanjit A. Seshia that provides a modern introduction to embedded systems.
</li>
<li>Vaandrager, F., <a href="http://www.cs.ru.nl/~fvaan/PV/what_is_a_good_model.html">What is a good model</a>, Unpublished note, 2010
</li>
<li>
Technical journals and conference papers, e.g. Computer Aided
Verification (CAV), Tools and Algorithms for the Construction of
Systems (TACAS)</li>
</ul>

# Other Resources

<p>
<a href="http://spinroot.com/spin/whatispin.html">
<img class="image-responsive pull-right" src="assets/images/spinlogo2_medium.gif"
     alt="SPIN Logo"    width="80" /></a>
</p>
<p>
<strong><a href="http://spinroot.com/spin/whatispin.html">SPIN</a></strong><br/>
"Spin is a popular open-source software tool, used by thousands of
people worldwide, that can be used for the formal verification of
distributed software systems. The tool was developed at Bell Labs in the
original Unix group of the Computing Sciences Research Center, starting in
1980. The software has been available freely since 1991, and continues to
evolve to keep pace with new developments in the field. In April 2002 the tool
was awarded the prestigious System Software Award for 2001 by the ACM." [<a
  href="http://awards.acm.org/award_winners/holzmann_1625680.cfm">Holzmann</a>]
</p> <p> The main focus of this module, in weeks 1-4, is on the theory and
practical application of this tool to the modelling and analysis of embedded
systems. It is essential that you use the tool extensively on a variety of lab
exercises. The tool is installed in PB Lab F1 on the Linux machines. It is also
available free for use on your own machines -- see the <a
  href="http://spinroot.com/spin/Man/README.html">download</a> instructions.  </p>

<ul>
<li><a href="http://spinroot.com/spin/Man/3_SpinGUI.html">Getting Started with SPIN</a></li>
<li><a href="http://spinroot.com/spin/Man/">SPIN online references</a></li>
</ul>

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
The main focus of this module, in weeks 5-8, is on the theory and
practical application of this tool to the modelling and analysis of
embedded systems. It is essential that you use the tool extensively on
a variety of lab exercises. The tool is installed in PB Lab F1 on the
Linux machines. It is also available free for use on your own machines.
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

# Professionalism, ethics and standards


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
Hennell,M., Woodcock,J. and Woodward,M., <a href="http://www.fuji-setsu.co.jp/files/IEC61508_ldra.pdf">The Safety Integrity Levels Of IEC 61508 And A Revised Proposal</a>, Embedded Systems Show, 2006. (<a href="{{site.raurl}}/reading/hww06.pdf">Local copy</a>)
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

# Security

<ul>
<li>Anderson, R., <em>Security Engineering: A guide to building dependable distributed systems</em> (2nd edition), John Wiley, 2008 [<a href="{{site.raurl}}/reading/and08.pdf">local copy of Chapter 5: Cryptography</a>]</li>
<li> Halperin, D., Heydt-Benjamin, T.S., Ransford, B.,  Clark, S.S., Defend, B., Morgan, W., Fu, K., Kohno, T. and Maisel, W.H., <em>Pacemakers and Implantable Cardiac Defibrillators: Software Radio Attacks and Zero-Power Defenses</em>, IEEE Symposium on Security and Privacy, 129-142, May, 2008 [<a href="{{site.raurl}}/reading/hhr08.pdf">pdf</a>]</li>
<li> Koopman, P., <em>Embedded system security</em>, IEEE Computer, 37(7): 95-97, July 2004 [<a href="{{site.raurl}}/reading/koo04.pdf">pdf</a>]</li>
<li> Karl Koscher, Alexei Czeskis, Franziska Roesner, Shwetak Patel, and Tadayoshi Kohno, Stephen Checkoway, Damon McCoy, Brian Kantor, Danny Anderson, Hovav Shacham, and Stefan Savage, <em>Experimental Security Analysis of a Modern Automobile</em>, IEEE Symposium on Security and Privacy 2010, 447-462, 2010 [<a href="{{site.raurl}}/reading/kcr10.pdf">pdf</a>]</li>
<li> Maggi, P. and Sisto, R., <em>Using SPIN to verify security properties of cryptographic protocols</em>, Proceedings of SPIN Workshop 2002, LNCS 2318, 187-204, Springer Verlag, 2002 [<a href="{{site.raurl}}/reading/ms02.pdf">pdf</a>]</li>
<li> Ryan, P., Schneider, S., Goldsmith, M. and Lowe, G., <em>Modelling and analysis of security protocols: the CSP approach</em>, Addison Wesley, 2000 [<a href="{{site.raurl}}/reading/rsg00.pdf">pdf</a>]</li>
</ul>

