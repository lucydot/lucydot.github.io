+++
date = "2017-05-04T13:47:56+01:00"
tags = []
title = "Roadmap"
type = "post"
categories = []

+++

This is a personal research roadmap, inspired by the [personal mathematical roadmap of Julia Wolf](http://www.juliawolf.org/research/roadmap.shtml). It is an evolving collection of tools, papers, websites and online lectures related to computational energy materials research. It is not an exhaustive list but highlights what I have found particularly useful. The purpose is to provide a subjective guide for those new to the research area, and a reminder for myself.

For online tools I use a pound sign to denote that there is an associated cost and a star to denote open source projects. If you use any of the tools please [cite accordingly](https://www.software.ac.uk/how-cite-software). If any links are broken, then please [let me know](mailto:l.whalley@northumbria.ac.uk).

-----

<big><b>
General research toolkit</b></big>

- Paper management and sharing: [Zotero](https://www.zotero.org/)<sup>* </sup> 
- Communication: [Slack](slack.com)<sup>£</sup> or it's open source sister [Zulip](zulipchat.com)<sup>* </sup> (note that both feature built-in video conferencing).
- Academic websites: Build it using a static site generator such as [Hugo](gohugo.io)<sup>* </sup> or [Jekyll](jekyllrb.com)<sup>* </sup>, and host it using [Github](github.com).
- Presentations: write it in [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), convert it to html using [reveal-md](https://github.com/webpro/reveal-md)<sup>* </sup> and host it using [Github](github.com).
- Notetaking: [simplenote](simplenote.com)<sup>* </sup>  which syncs with [nvALT](https://brettterpstra.com/projects/nvalt/)<sup>* </sup> on the Mac, and [MacDown](https://macdown.uranusjr.com/)<sup>* </sup>.

<big><b>
Computing (local)</b></big>

- Operating System: I find that using a unix-based system is easiest for code development, and that there are less "why doesn't this work?" moments with a Mac. (Although I haven't used a linux OS for almost 10 years; [ubuntu]()<sup>* </sup> has most likely improved a lot in that time)
- Hardware: For post-processing, writing code and other computationally lightweight tasks I use a MacBook Air with an external monitor, keyboard and [curiously shaped ergonomic mouse](https://www.rsi-shop.co.uk/products/penguin-ambidextrous-vertical-mouse-medium-wired-usb.asp). I have an iMac in the office which can also do some lightweight DFT.
- Back-ups: For local machines I use a combination of [Dropbox](dropbox.com)<sup>£ </sup>, [Github](github.com) and an external drive.

<big><b>
Computing (high performance)</b></big>

- Computer time: [Materials Chemistry Consortium](https://www.ucl.ac.uk/klmc/mcc/) for access to the Archer/Archer2 (Tier-1 national supercomputer), and [Prace](https://prace-ri.eu/) for access to Tier-0 HPC (European level).
- Storage: [Research Data Facility on Archer](https://www.archer.ac.uk/documentation/rdf-guide/).

<big><b>
Textbooks</b></big>

- Condensed Matter: [Principles of the theory of solids](https://www.cambridge.org/core/books/principles-of-the-theory-of-solids/F9E87699164B7094168277D4867EE4FC) and [Electrons and Phonons](https://global.oup.com/academic/product/electrons-and-phonons-9780198507796?cc=gb&lang=en&) by John Ziman.
- Other: [Models of disorder](https://www.cambridge.org/gb/academic/subjects/physics/condensed-matter-physics-nanoscience-and-mesoscopic-physics/models-disorder-theoretical-physics-homogeneously-disordered-systems?format=PB&isbn=9780521292801) by John Ziman.
- Electronic structure: [Electronic structure and the properties of solids](https://store.doverpublications.com/0486660214.html) by Walter Harrison
- Defects: [Defects and defect processes in Nonmetallic Solids](https://books.google.co.uk/books/about/Defects_and_Defect_Processes_in_Nonmetal.html?id=BNh4AAAAIAAJ&redir_esc=y) by Hayes and Stoneham
- Phonons: Lattice Dynamics by Martin Dove 
- PHotovoltaics: [The Physics of Solar Cells](https://www.worldscientific.com/worldscibooks/10.1142/p276) by Jenny Nelson

<big><b>
Electronic structure</b></big>

- Density Functional Theory: [Vasp](www.vasp.at)<sup>£</sup> and [ASE](https://wiki.fysik.dtu.dk/ase/index.html)<sup>* </sup>
- Analysis: [vasppy](https://github.com/bjmorgan/vasppy)<sup>* </sup>, [effmass](https://github.com/lucydot/effmass)<sup>* </sup>, [kgrid](https://github.com/WMD-group/kgrid)<sup>* </sup> and [PolaronMobility](https://github.com/jarvist/PolaronMobility.jl)<sup>* </sup>
- Plotting: [sumo](https://sumo.readthedocs.io/en/latest/?badge=latest)<sup>* </sup>
- Visualisation: [Vesta](https://jp-minerals.org/vesta/en/)
- Crystal structures database: [ICSD](https://icsdoffsite.psds.ac.uk/search/basic.xhtml;jsessionid=DBCA48F5394A5B0C1ED27257E58309F8)
- Property databases: [Materials Project](https://materialsproject.org/) (powered by [pymatgen](https://pymatgen.org/)<sup>* </sup>) and [Semiconductors: Data Handbook](https://link.springer.com/book/10.1007/978-3-642-18865-7) by Otfried Madelung

<big><b>
Defects</b></big>

- Processing: TODO
- Corrections: TODO
- Review articles: TODO

<big><b>
Phonons</b></big>

- Calculators: [phonopy](https://phonopy.github.io/phonopy/)<sup>* </sup> (harmonic and quasi-harmonic), [phono3py](https://phonopy.github.io/phono3py/)<sup>* </sup> (third order phonon-phonon interactions)
- Processing: [ModeMap](https://github.com/JMSkelton/ModeMap)<sup>* </sup>, [JuliaPhonons](https://github.com/jarvist/Julia-Phonons)<sup>* </sup>, [ASCIIphonons](https://github.com/ajjackson/ascii-phonons)<sup>* </sup>
- Review articles: TODO
- Textbooks: [Inbtroduction to Lattice Dynamics](https://www.cambridge.org/core/books/introduction-to-lattice-dynamics/85943FCCF2BA2797CE53D96D3A8BFCBF) by Martin Dove.

<big><b>
Photovoltaics</b></big>

- Efficiency tables: [NREL](https://www.nrel.gov/pv/cell-efficiency.html), [JPhys Energy emerging inorganic](https://iopscience.iop.org/article/10.1088/2515-7655/ab2338)

<big><b>
Python</b></big>

- IDE: PyCharm
- version control: git
- code repository: Github
- interactive notebook: Jupyter / Jupyter Lab
- general scientific computing: matplotlib, pandas, numpy
- testing: pytest
- continuous integration: Travis CI
- documentation: Automatically generate and build online documentation using Sphinx and ReadTheDocs.

<big><b>
Machine Learning</b></big>

- TODO

<big><b>
Publications</b></big>

- Writing: LaTeX using the Sublime text editor, Overleaf for collaborative documents
- Graphics: Omnigraffle for schematics and matplotlib for plotting
- Software journals: JOSS
- Miscellaneous: doi2bib

<big><b>
Research and travel funding</b></big></br>
(note that this is very much a *wish list*!)

- EPSRC: [New investigator award](https://epsrc.ukri.org/funding/applicationprocess/routes/newac/nia/), [Fellowship programme](https://epsrc.ukri.org/skills/fellows/overview/)
- UKRI: [Future Leaders Fellowships](https://www.ukri.org/funding/funding-opportunities/future-leaders-fellowships/)
- Royal Society: [Dorothy Hodgkins fellowship](https://royalsociety.org/grants-schemes-awards/grants/dorothy-hodgkin-fellowship/)

<big><b>
Professional communities</b></big>

- Institute of Physics
- Royal Society of Chemistry
- Thomas Young Centre
- CECAM
- MRS
- Gordon Conference
- Software Sustainability Institute
- RSESociety


<big><b>
Blogs and academic websites</b></big>

- A set of useful links is maintained by Aron Walsh on his group website: http://wmd-group.github.io/links/
- Blogs: [Aron Walsh](), Jarvist Frost, 
- Best practices in computational chemistry from Guido von Rudorff: https://guido.vonrudorff.de/best-practices/

<big><b>
Video lectures</b></big>

- ML4science channel: https://www.youtube.com/c/ML4Science/live
- CECAM channel: https://www.youtube.com/channel/UCwMTf03fJ_ECmsDsqHOsSuA
- Solid State Physics in a Nutshell channel: https://www.youtube.com/channel/UCFgtgeXkgWr1MsOTftce5BA

<big><b>
Miscellaneous</b></big>

- Motherhood and academia blog:[Mamaisanacademic](https://mamaisanacademic.wordpress.com/blog/)
- Keith Butler's Materials Hipster: https://keeeto.github.io/tag/materials_hipster/