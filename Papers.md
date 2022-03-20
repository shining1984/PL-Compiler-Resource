# The Papers about PL and Compiler

## Compilers

1. [*An Efficient Method of Computing Static Single Assignment Form*](http://pages.cs.wisc.edu/~fischer/cs701.f08/ssa.pdf)

2. [*Simple and Efficient Construction of Static Single Assignment Form - CC 2013*](https://compilers.cs.uni-saarland.de/papers/bbhlmz13cc.pdf)

3. [*A Brief History of JIT Compilation*](http://eecs.ucf.edu/~dcm/Teaching/COT4810-Spring2011/Literature/JustInTimeCompilation.pdf) -John Aycock

### Compilers -- Optimization

1. [Lazy code motion](https://dl.acm.org/doi/10.1145/143095.143136) --Jens Knoop, Oliver Rüthing, Bernhard Steffen. 1992

2. [*A New Algorithm for Partial Redundancy Elimination based on SSA Form*](https://www.researchgate.net/publication/2460226) --Fred Chow, Sun Chan, Robert Kennedy, Shin-Ming Liu, Raymond Lo, Peng Tu. 1997

3. [Lazy code motion](https://dl.acm.org/doi/10.1145/989393.989439) --Jens Knoop, Oliver Rüthing, Bernhard Steffen. 2004

#### Compilers -- Optimization -- Peephole Optimization

1. [*Peephole optimization*](https://dl.acm.org/doi/10.1145/364995.365000) --W. M. McKeeman. 1965

2. [*Object Code Optimization*](https://dl.acm.org/doi/10.1145/362835.362838) --Edward S. Lowry, C. W. Medlock. 1969

3. [*A Compact, Machine-Independent Peephole Optimizer*](https://dl.acm.org/doi/10.1145/567752.567753) --Christopher W. Fraser. 1979

4. [*The Design and Application of a Retargetable Peephole Optimizer*](https://dl.acm.org/doi/10.1145/357094.357098) --Davidson J. W, Fraser C. W. 1980

5. [*Code Selection Through Object Code Optimization*](https://dl.acm.org/doi/10.1145/1780.1783) --Davidson J. W, Fraser C. W. 1984

6. [*Fifty years of peephole optimization*](https://www.currentscience.ac.in/Volumes/108/12/2186.pdf) --Pinaki Chakraborty. 2015

### Compilers -- Instruction Selection

1. [*Code Selection Through Object Code Optimization*](https://dl.acm.org/doi/10.1145/1780.1783) --Davidson J. W, Fraser C. W. 1984

2. [*Survey on Instruction Selection*](https://arxiv.org/ftp/arxiv/papers/1306/1306.4898.pdf) --gabriel s. hjort blindell. 2013.

### Compilers -- Register Allocation

#### Compilers -- Register Allocation -- Graph Coloring

1. [*Register Allocation via Coloring*](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.452.8606&rep=rep1&type=pdf) --Gregory J.Chaitin etc. 1981

2. [*Register Allocation and Spilling via Graph Coloring*](https://cs.gmu.edu/~white/CS640/p98-chaitin.pdf) -- G.J.Chaitin. 1982

   core algorithm: [*On the Geographical Problem of the Four colours*](https://www.jstor.org/stable/2369235?seq=1#metadata_info_tab_contents)  --A. B. Kempe. 1879

3. [*Improvements to Graph Coloring Register Allocation*](https://www.researchgate.net/publication/2392358_Improvements_to_Graph_Coloring_Register_Allocation) --Preston Briggs, Keith D.Cooper, Linda Torczon. 1994

4. [*Iterated Register Coalescing*](http://www.cse.iitm.ac.in/~krishna/courses/2012/odd-cs6013/george.pdf) --Lal George, Andrew W.Appel. 1996

5. [*Optimistic Register Coalescing*](https://ieeexplore.ieee.org/document/727246) --Jinpyo Park, Soo-Mook Moon. 1998

6. [*Optimistic Register Coalescing*](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.39.7615&rep=rep1&type=pdf) --Jinpyo Park, Soo-Mook Moon. 2004

7. [*On the Complexity of Register Coalescing*](https://hal-lara.archives-ouvertes.fr/hal-02102282/file/RR2006-15.pdf) --Florent Bouchez, Alain Darte, Fabrice Rastello. 2007

#### Compilers -- Register Allocation -- Linear Scan

1. [*Linear Scan Register Allocation*](http://web.cs.ucla.edu/~palsberg/course/cs132/linearscan.pdf) --MASSIMILIANO POLETTO, VIVEK SARKAR. 1999

   related: [*Algorithms for Minimum Coloring, Maximum Clique, Minimum Covering by Cliques, and Maximum Independent Set of a Chordal Graph*]() --Fanica Gavril. 1972

2. [*Quality and Speed in Linear-scan Register Allocation*](https://dash.harvard.edu/bitstream/handle/1/34325454/tr-21-97.pdf;jsessionid=4FF577927DA65DE17A72800864F6F27C?sequence=1)  --Omri Traub, Glenn Holloway, Michael D. Smith. 1998

3. [*Linear Scan Register Allocation in the Context of SSA Form and Register Constraints*](https://link.springer.com/content/pdf/10.1007%2F3-540-45937-5_17.pdf)  --Hanspeter Mossenbock, Michael Pfeiffer. 2002

4. [*Optimized Interval Splitting in a Linear Scan Register Allocator*](https://www.usenix.org/legacy/events/vee05/full_papers/p132-wimmer.pdf)  --Christian Wimmer, Hanspeter Mossenbock. 2005

5. [*Extended Linear Scan: an Alternate Foundation for Global Register Allocation*](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.94.4590&rep=rep1&type=pdf) --Vivek Sarkar, Rajkishore Barik. 2007

#### Compilers -- Register Allocation -- SSA Based Register Allocation

Note: Any of the register allocation approaches can be adapted to run on SSA-form programs.

1. [*Allocation de registres et vidage en memoire(Master's thesis)*] --Florent Bouchez. 2005

2. [*Polynomial-time graph coloring register allocation*]  --Philip Brisc, Foad Dabiri, Jamie Macbeth, Majid Sarrafzadeh. 2005

3. [*Register Allocation for Programs in SSA-Form*](https://compilers.cs.uni-saarland.de/papers/ssara.pdf)  --Sebastian Hack, Daniel Grund, and Gerhard Goos. 2006

4. [*Linear Scan Register Allocation on SSA Form*](http://www.christianwimmer.at/Publications/Wimmer10a/Wimmer10a.pdf)  --Christian Wimmer, Michael Franz. 2010

#### Compilers -- Register Allocation -- Others

1. [*A Survey on Register Allocation*](http://compilers.cs.ucla.edu/fernando/publications/drafts/survey.pdf)  -- Fernando Magno Quint˜ao Pereira. 2008

2. [*A SURVEY OF REGISTER ALLOCATION TECHNIQUES*](https://jonathan.protzenko.fr/papers/register09.pdf)  -- Jonathan Protzenko. 2009

3. [*A Detailed Analysis of the LLVM’s Register Allocators*](https://www.researchgate.net/publication/261461454_A_Detailed_Analysis_of_the_LLVM's_Register_Allocators) --Tiago Cariolano de Souza Xavier, George Souza Oliveira, Ewerton Daniel de Lima and Anderson Faustino da Silva. 2012

## Virtual Machine

1.[*A Unified Theory of Garbage Collection*](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.143.6619&rep=rep1&type=pdf)  --David F.Bacon, Perry Cheng, V.T.Rajan. 2004

## The History of Programming Languages

1. [*The Development of the C Language*](https://www.bell-labs.com/usr/dmr/www/chist.html) --Dennis M. Ritchie

2. [*APL since 1978*](https://dl.acm.org/doi/pdf/10.1145/3386319) --Roger K. W. Hui, Morten J. Kromberg

3. [*Thriving in a crowded and changing world: C++ 2006–2020*](https://dl.acm.org/doi/pdf/10.1145/3386320) --Bjarne Stroustrup

4. [*A history of Clojure*](https://dl.acm.org/doi/pdf/10.1145/3386321) --Rich Hickey

5. [*History of coarrays and SPMD parallelism in Fortran*](https://dl.acm.org/doi/pdf/10.1145/3386322) --John Reid, Bill Long, Jon Steidel

6. [*Origins of the D Programming Language*](https://dl.acm.org/doi/pdf/10.1145/3386323) --Walter Bright, Andrei Alexandrescu, Michael Parker

7. [*Evolution of Emacs Lisp*](https://dl.acm.org/doi/pdf/10.1145/3386324) --Stefan Monnier, Michael Sperber

8. [*The early history of F#*](https://dl.acm.org/doi/pdf/10.1145/3386325) --Don Syme

9. [*A history of the Groovy programming language*](https://dl.acm.org/doi/pdf/10.1145/3386326) --Paul King

10. [*JavaScript: the first 20 years*](https://dl.acm.org/doi/pdf/10.1145/3386327) --Allen Wirfs-Brock, Brendan Eich

11. [*LabVIEW*](https://dl.acm.org/doi/pdf/10.1145/3386328) --Jeffrey Kodosky

12. [*History of Logo*](https://dl.acm.org/doi/pdf/10.1145/3386329) --Cynthia Solomon, Brian Harvey, Ken Kahn, Henry Lieberman, Mark L. Miller, Margaret Minsky, Artemis Papert, Brian Silverman

13. [*Hygienic macro technology*](https://dl.acm.org/doi/pdf/10.1145/3386330) --William D. Clinger, Mitchell Wand

14. [*A history of MATLAB*](https://dl.acm.org/doi/pdf/10.1145/3386331) --Cleve Moler, Jack Little

15. [*The origins of Objective-C at PPI/Stepstone and its evolution at NeXT*](https://dl.acm.org/doi/pdf/10.1145/3386332) --Brad J. Cox, Steve Naroff, Hansen Hsu

16. [*A history of the Oz multiparadigm language*](https://dl.acm.org/doi/pdf/10.1145/3386333) --Peter Van Roy, Seif Haridi, Christian Schulte, Gert Smolka

17. [*S, R, and data science*](https://dl.acm.org/doi/pdf/10.1145/3386334) --John M. Chambers

18. [*The evolution of Smalltalk: from Smalltalk-72 through Squeak*](https://dl.acm.org/doi/pdf/10.1145/3386335) --Daniel Ingalls

19. [*The history of Standard ML*](https://dl.acm.org/doi/pdf/10.1145/3386336) --David MacQueen, Robert Harper, John Reppy

20. [*Verilog HDL and its ancestors and descendants*](https://dl.acm.org/doi/pdf/10.1145/3386337) --Peter Flake, Phil Moorby, Steve Golson, Arturo Salz, Simon Davidmann

Notes: 2-20为HOPL IV: History of Programming Languages会议文章，官方网址(https://hopl4.sigplan.org/).

21. [*Thriving in a Crowded and Changing World C++ 2006–2020*](https://www.stroustrup.com/hopl20main-p5-p-bfc9cd4--final.pdf) --BJARNE STROUSTRUP