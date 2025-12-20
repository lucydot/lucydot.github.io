+++
date = "2017-05-04T13:47:56+01:00"
tags = []
title = "Ingredients"
type = "draft"
categories = []

+++

This is an ingredients list for research, inspired by the [personal mathematical roadmap of Julia Wolf](http://www.juliawolf.org/research/roadmap.shtml). It is a (slowly) evolving collection of tools, papers, websites and online lectures related to computational energy materials research. It is not exhaustive but highlights what we have found particularly useful. 

For online tools we use a pound sign to denote that there is an associated cost and a star to denote open source projects. If you use any of the tools please [cite accordingly](https://www.software.ac.uk/how-cite-software).

-----

<big><b>
General research toolkit</b></big>

- Paper management and sharing: [Zotero](https://www.zotero.org/)<sup>* </sup> 
- Communication: [Slack](http://slack.com)<sup>£</sup> or it's open source sister [Zulip](http://zulipchat.com)<sup>* </sup>.
- Academic websites: Build it using a static site generator such as [Hugo](http://gohugo.io)<sup>* </sup> or [Jekyll](http://jekyllrb.com)<sup>* </sup>, and host it using [Github](http://github.com).
- Presentations: write it in [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), convert it to html using [reveal-md](https://github.com/webpro/reveal-md)<sup>* </sup> and host it using [Github](http://github.com).
- Notetaking: [simplenote](http://simplenote.com)<sup>* </sup>  which syncs with [nvALT](https://brettterpstra.com/projects/nvalt/)<sup>* </sup> on the Mac.
- Text editor: For text with minimal formatting (e.g. abstracts) I write in Markdown using the [MacDown](https://macdown.uranusjr.com/)<sup>* </sup> editor. For larger documents (e.g. funding applications) I write in LaTeX using the [Sublime](https://www.sublimetext.com/)<sup>£</sup> text editor.

<big><b>
Computing (local)</b></big>

- Operating System: I find that using a unix-based system is easiest for code development, and that there are less "why doesn't this work?" moments with a Mac.
- Hardware: For post-processing, writing code and other computationally lightweight tasks I use a MacBook Air and iMac.
- Back-ups and syncing: For backing up my workstation I use an external drive with Time Machine, for syncing between my laptop and workstation I use a combination of [Dropbox](http://dropbox.com)<sup>£ </sup> and [Github](http://github.com).

<big><b>
Computing (high performance)</b></big>

- Computer time: [Materials Chemistry Consortium](https://www.ucl.ac.uk/klmc/mcc/) for access to the Tier-1 (national) supercomputer Archer/Archer2, and [Prace](https://prace-ri.eu/) for access to Tier-0 (European level) HPC.
- Storage: [Research Data Facility on Archer](https://www.archer.ac.uk/documentation/rdf-guide/).

<big><b>
Electronic structure</b></big>

- Density Functional Theory: [FHI-aims](https://fhi-aims.org/), [Vasp](http://www.vasp.at)<sup>£</sup> and [ASE](https://wiki.fysik.dtu.dk/ase/index.html)<sup>* </sup>.
- Plotting: [sumo](https://sumo.readthedocs.io/en/latest/?badge=latest)<sup>* </sup>
- Visualisation: [Vesta](https://jp-minerals.org/vesta/en/)
- Crystal structures database: [ICSD](https://icsdoffsite.psds.ac.uk/search/basic.xhtml;jsessionid=DBCA48F5394A5B0C1ED27257E58309F8)
- Property databases: [Materials Project](https://materialsproject.org/) (powered by [pymatgen](https://pymatgen.org/)<sup>* </sup>) and [Semiconductors: Data Handbook](https://link.springer.com/book/10.1007/978-3-642-18865-7) by Otfried Madelung.

<big><b>
Defects</b></big>

- Processing: [CPLAP](https://github.com/jbuckeridge/cplap) (stable chemical potential range), [scfermi](https://github.com/jbuckeridge/sc-fermi) (self-consistent Fermi level), [CarrierCapture.jl](https://github.com/WMD-group/CarrierCapture.jl)<sup>* </sup> (carrier capture rates)
- Corrections: [sxdefectalign](https://sxrepo.mpie.de/projects/sphinx-add-ons/files) (implements the [Freysoldt, Neugebauer and van de Walle scheme](ttps://doi.org/10.1002/pssb.201046289))
- Review articles: [Tutorial: Defects in semiconductors—Combining experiment and theory](https://doi.org/10.1063/1.4948245) by Audrius Alkasukas et al, [Defects and defect processes](https://doi.org/10.1080/00018737900101395) by Marshall Stoneham, [First-principles calculations for defects and impurities: Applications to III-nitrides](https://doi.org/10.1063/1.1682673) by Chris van de Walle, [Quick-start guide for first-principles modelling of point defects in crystalline materials](https://doi.org/10.1088/2515-7655/aba081) by Sunghyun Kim et al.

<big><b>
Phonons</b></big>

- Calculators: [phonopy](https://phonopy.github.io/phonopy/)<sup>* </sup> (harmonic and quasi-harmonic), [phono3py](https://phonopy.github.io/phono3py/)<sup>* </sup> (third order phonon-phonon interactions)
- Processing: [ModeMap](https://github.com/JMSkelton/ModeMap)<sup>* </sup>, [JuliaPhonons](https://github.com/jarvist/Julia-Phonons)<sup>* </sup>
- Visualisation: [ASCIIphonons](https://github.com/ajjackson/ascii-phonons)<sup>* </sup>, [phonon website](http://henriquemiranda.github.io/phononwebsite/phonon.html)<sup>* </sup>

<big><b>
Photovoltaics</b></big>

- Efficiency tables: [NREL](https://www.nrel.gov/pv/cell-efficiency.html), [JPhys Energy emerging inorganic](https://iopscience.iop.org/article/10.1088/2515-7655/ab2338)

<big><b>
Python</b></big>

- Code editor: [Sublime](https://www.sublimetext.com/)<sup>£</sup>
- IDE: [pycharm](https://www.jetbrains.com/pycharm/)<sup>£</sup>
- Version control: [git](https://git-scm.com/) and the [Version Control with Git](https://swcarpentry.github.io/git-novice/)<sup>* </sup> Software carpentry course (available online or in person)
- Code repository: [Github](http://github.com)
- Interactive notebook: [Jupyter](https://jupyter.org/)<sup>* </sup> and [Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/#)<sup>* </sup> for interactive code development. The [binder](https://mybinder.org/)<sup>* </sup> web app so that others can easily interact with your notebooks.
- Python scientific computing stack: [matplotlib](http://matplotlib.org)<sup>* </sup> (plotting), [pandas](http://pandas.pydata.org)<sup>* </sup> (data analysis), [numpy](http://numpy.org)<sup>* </sup> (arrays)
- Testing: [pytest](http://docs.pytest.org)<sup>* </sup>
- Continuous integration: Github Actions.
- Documentation: [Mkdocs](https://www.mkdocs.org/).

<big><b>
Publications</b></big>

- Typesetting: I use LaTeX with the [mhchem](https://ctan.org/pkg/mhchem?lang=en)<sup>* </sup>  package for formatting chemical equations 
- Equations: [LaTexit](https://www.chachatelier.fr/latexit/)
- Text editors: I use the [Sublime](https://www.sublimetext.com/)<sup>£</sup> text editor and, for collaborative LaTeX documents, [Overleaf](http://overleaf.com) 
- Bibliography: [doi2bib](https://www.doi2bib.org/)
- Graphics: [Omnigraffle](https://www.omnigroup.com/omnigraffle)<sup>£</sup> for schematics and [matplotlib](https://matplotlib.org/)<sup>* </sup> for plotting
- Software journals: [The Journal of Open Source Software](https://joss.theoj.org/)<sup>* </sup>

<big><b>
Research funding</b></big></br>
(note that this is very much a *wish list*!)

- EPSRC: [New investigator award](https://epsrc.ukri.org/funding/applicationprocess/routes/newac/nia/), [Fellowship programme](https://epsrc.ukri.org/skills/fellows/overview/)
- UKRI: [Future Leaders Fellowships](https://www.ukri.org/funding/funding-opportunities/future-leaders-fellowships/)
- Royal Society: [Dorothy Hodgkins fellowship](https://royalsociety.org/grants-schemes-awards/grants/dorothy-hodgkin-fellowship/)

<big><b>
Professional communities</b></big>

- [Institute of Physics](http://www.iop.org/) 
- [Royal Society of Chemistry](https://www.rsc.org/)
- [Thomas Young Centre](https://www.thomasyoungcentre.org/)
- [CECAM - Centree Europeen de Calcul Atomique et Molecuaire](https://www.cecam.org/)
- [Materials Research Society](http://www.mrs.org)
- [Gordon Research Conference series: Defects in Semiconductors](https://www.grc.org/defects-in-semiconductors-grs-conference/2020/) 
- [Software Sustainability Institute](https://www.software.ac.uk/)
- [Society of Research Software Engineers](https://society-rse.org/)

<big><b>
Blogs and group websites</b></big>

- A set of useful links is maintained by the [Materials Design Group](http://wmd-group.github.io/links/)
- Best practices in computational chemistry from [Guido von Rudorff](https://guido.vonrudorff.de/best-practices/)
- Various tips and tricks for computational chemistry in the appendices of the [HackingMaterials handbook](https://hackingmaterials.com/2017/01/08/our-group-handbook/)
- Setting up a mac for computational chemistry from [thelostelectron blog](https://thelostelectron.wordpress.com/)

<big><b>
Textbooks</b></big>

- Condensed Matter: [Principles of the theory of solids](https://www.cambridge.org/core/books/principles-of-the-theory-of-solids/F9E87699164B7094168277D4867EE4FC) and [Electrons and Phonons](https://global.oup.com/academic/product/electrons-and-phonons-9780198507796?cc=gb&lang=en&) by John Ziman.
- Electronic structure: [Electronic structure and the properties of solids](https://store.doverpublications.com/0486660214.html) by Walter Harrison
- Defects: [Defects and defect processes in Nonmetallic Solids](https://books.google.co.uk/books/about/Defects_and_Defect_Processes_in_Nonmetal.html?id=BNh4AAAAIAAJ&redir_esc=y) by Hayes and Stoneham
- Phonons: [Introduction to Lattice Dynamics](https://www.cambridge.org/core/books/introduction-to-lattice-dynamics/85943FCCF2BA2797CE53D96D3A8BFCBF) by Martin Dove
- Photovoltaics: [The Physics of Solar Cells](https://www.worldscientific.com/worldscibooks/10.1142/p276) by Jenny Nelson
- Other: [Models of disorder](https://www.cambridge.org/gb/academic/subjects/physics/condensed-matter-physics-nanoscience-and-mesoscopic-physics/models-disorder-theoretical-physics-homogeneously-disordered-systems?format=PB&isbn=9780521292801) by John Ziman.

<big><b>
Video lectures</b></big>

- [ML4science channel](https://www.youtube.com/c/ML4Science/live)
- [CECAM channel](https://www.youtube.com/channel/UCwMTf03fJ_ECmsDsqHOsSuA)
- [Solid State Physics in a Nutshell channel](https://www.youtube.com/channel/UCFgtgeXkgWr1MsOTftce5BA)
- [VASP video series](https://www.youtube.com/@vasp8588/videos)
- [Materials Project seminars](https://www.youtube.com/@MaterialsProject/videos)

<big><b>
Teaching resources</b></big>

- Small Teaching by James M. Lang connects pedagogical theory with some easily implementable ideas for the classroom
- Teaching Tech Together by Greg Wilson. Greg Wilson co-founded Software Carpentry and this book expands on the excellent instructor training that is delivered by the organisation.

<big><b>
Miscellaneous</b></big>

- Bird of passage by Rudolf Peierls. This is one of my very favourite books. It is an autobiography from a German born physicist who travelled to the UK and kick-started the Manhattan project with the [Frisch-Peierls memorandum](https://en.wikipedia.org/wiki/Frisch%E2%80%93Peierls_memorandum). It provides lots of interesting context around the early developments in quantum mechanics and solid state physics.

