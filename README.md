# Python citations
bibtex for various Python science and machine learning software.

Copy the contents of [main.bib](https://raw.githubusercontent.com/MilesCranmer/python_citations/master/main.bib) into your
bib file. Cite the packages with the following code (remove any you don't use).

```latex
\texttt{numpy} \cite{numpy},
\texttt{scipy} \cite{scipy},
\texttt{jupyter} \cite{jupyter},
\texttt{sklearn} \cite{sklearn},
\texttt{matplotlib} \cite{matplotlib},
\texttt{pandas} \cite{pandas},
\texttt{torch} \cite{torch},
\texttt{jax} \cite{jax},
\texttt{sympy} \cite{sympy},
\texttt{tensorflow} \cite{tensorflow},
\texttt{torch\_geometric} \cite{torch_geometric},
\texttt{astropy} \cite{astropy},
\texttt{xarray} \cite{xarray},
\texttt{cartopy} \cite{cartopy},
\texttt{pytorch\_lightning} \cite{pytorch_lightning},
\texttt{julia} \cite{julia},
```


## `numpy`
```bibtex

@article{numpy,
	title = {Array programming with {NumPy}},
	volume = {585},
	issn = {1476-4687},
	url = {https://doi.org/10.1038/s41586-020-2649-2},
	doi = {10.1038/s41586-020-2649-2},
	abstract = {Array programming provides a powerful, compact and expressive syntax for accessing, manipulating and operating on data in vectors, matrices and higher-dimensional arrays. NumPy is the primary array programming library for the Python language. It has an essential role in research analysis pipelines in fields as diverse as physics, chemistry, astronomy, geoscience, biology, psychology, materials science, engineering, finance and economics. For example, in astronomy, NumPy was an important part of the software stack used in the discovery of gravitational waves1 and in the first imaging of a black hole2. Here we review how a few fundamental array concepts lead to a simple and powerful programming paradigm for organizing, exploring and analysing scientific data. NumPy is the foundation upon which the scientific Python ecosystem is constructed. It is so pervasive that several projects, targeting audiences with specialized needs, have developed their own NumPy-like interfaces and array objects. Owing to its central position in the ecosystem, NumPy increasingly acts as an interoperability layer between such array computation libraries and, together with its application programming interface (API), provides a flexible framework to support the next decade of scientific and industrial analysis.},
	number = {7825},
	journal = {Nature},
	author = {Harris, Charles R. and Millman, K. Jarrod and van der Walt, Stéfan J. and Gommers, Ralf and Virtanen, Pauli and Cournapeau, David and Wieser, Eric and Taylor, Julian and Berg, Sebastian and Smith, Nathaniel J. and Kern, Robert and Picus, Matti and Hoyer, Stephan and van Kerkwijk, Marten H. and Brett, Matthew and Haldane, Allan and del Río, Jaime Fernández and Wiebe, Mark and Peterson, Pearu and Gérard-Marchant, Pierre and Sheppard, Kevin and Reddy, Tyler and Weckesser, Warren and Abbasi, Hameer and Gohlke, Christoph and Oliphant, Travis E.},
	month = sep,
	year = {2020},
	pages = {357--362}
}
```
  
## `scipy`
```bibtex
@ARTICLE{scipy,
       author = {{Virtanen}, Pauli and {Gommers}, Ralf and {Oliphant},
         Travis E. and {Haberland}, Matt and {Reddy}, Tyler and
         {Cournapeau}, David and {Burovski}, Evgeni and {Peterson}, Pearu
         and {Weckesser}, Warren and {Bright}, Jonathan and {van der Walt},
         St{\'e}fan J.  and {Brett}, Matthew and {Wilson}, Joshua and
         {Jarrod Millman}, K.  and {Mayorov}, Nikolay and {Nelson}, Andrew
         R.~J. and {Jones}, Eric and {Kern}, Robert and {Larson}, Eric and
         {Carey}, CJ and {Polat}, {\.I}lhan and {Feng}, Yu and {Moore},
         Eric W. and {Vand erPlas}, Jake and {Laxalde}, Denis and
         {Perktold}, Josef and {Cimrman}, Robert and {Henriksen}, Ian and
         {Quintero}, E.~A. and {Harris}, Charles R and {Archibald}, Anne M.
         and {Ribeiro}, Ant{\^o}nio H. and {Pedregosa}, Fabian and
         {van Mulbregt}, Paul and {Contributors}, SciPy 1. 0},
        title = "{SciPy 1.0: Fundamental Algorithms for Scientific
                  Computing in Python}",
      journal = {Nature Methods},
      year = "2020",
      volume={17},
      pages={261--272},
      adsurl = {https://rdcu.be/b08Wh},
      doi = {https://doi.org/10.1038/s41592-019-0686-2},
}
```

## `jupyter`
```bibtex
@CONFERENCE{jupyter,
	Author = {Thomas Kluyver and Benjamin Ragan-Kelley and Fernando P{\'e}rez and Brian Granger and Matthias Bussonnier and Jonathan Frederic and Kyle Kelley and Jessica Hamrick and Jason Grout and Sylvain Corlay and Paul Ivanov and Dami{\'a}n Avila and Safia Abdalla and Carol Willing},
	Booktitle = {Positioning and Power in Academic Publishing: Players, Agents and Agendas},
	Editor = {F. Loizides and B. Schmidt},
	Organization = {IOS Press},
	Pages = {87 - 90},
	Title = {{J}upyter {N}otebooks -- a publishing format for reproducible computational workflows},
	Year = {2016}}
```
## `pandas`

```bibtex
@INPROCEEDINGS{pandas,
  author    = { {W}es {M}c{K}inney },
  title     = { {D}ata {S}tructures for {S}tatistical {C}omputing in {P}ython },
  booktitle = { {P}roceedings of the 9th {P}ython in {S}cience {C}onference },
  pages     = { 56 - 61 },
  year      = { 2010 },
  editor    = { {S}t\'efan van der {W}alt and {J}arrod {M}illman },
  doi       = { 10.25080/Majora-92bf1922-00a }
}
```

## `sklearn`
```bibtex
@ARTICLE{sklearn,
  author  = {Fabian Pedregosa and Ga{{\"e}}l Varoquaux and Alexandre Gramfort and Vincent Michel and Bertrand Thirion and Olivier Grisel and Mathieu Blondel and Peter Prettenhofer and Ron Weiss and Vincent Dubourg and Jake Vanderplas and Alexandre Passos and David Cournapeau and Matthieu Brucher and Matthieu Perrot and {{\'E}}douard Duchesnay},
  title   = {{Scikit-learn: Machine Learning in Python}},
  journal = {{J}ournal of {M}achine {L}earning {R}esearch},
  year    = {2011},
  volume  = {12},
  number  = {85},
  pages   = {2825-2830},
  url     = {http://jmlr.org/papers/v12/pedregosa11a.html}
}
```

## `matplotlib`

```bibtex
@ARTICLE{matplotlib,
  author={J. D. {Hunter}},
  journal={{C}omputing in {S}cience \& {E}ngineering}, 
  title={{Matplotlib: A 2D Graphics Environment}}, 
  year={2007},
  volume={9},
  number={3},
  pages={90-95},}
```

## `torch`

```bibtex
@INCOLLECTION{torch,
	title = {{P}y{T}orch: {A}n {I}mperative {S}tyle, {H}igh-{P}erformance {D}eep {L}earning {L}ibrary},
	author = {Paszke, Adam and Gross, Sam and Massa, Francisco and Lerer, Adam and Bradbury, James and Chanan, Gregory and Killeen, Trevor and Lin, Zeming and Gimelshein, Natalia and Antiga, Luca and Desmaison, Alban and Kopf, Andreas and Yang, Edward and DeVito, Zachary and Raison, Martin and Tejani, Alykhan and Chilamkurthy, Sasank and Steiner, Benoit and Fang, Lu and Bai, Junjie and Chintala, Soumith},
	booktitle = {Advances in Neural Information Processing Systems 32},
	editor = {H. Wallach and H. Larochelle and A. Beygelzimer and F. d\textquotesingle Alch\'{e}-Buc and E. Fox and R. Garnett},
	pages = {8024--8035},
	year = {2019},
	publisher = {Curran Associates, Inc.},
	url = {http://papers.neurips.cc/paper/9015-pytorch-an-imperative-style-high-performance-deep-learning-library.pdf}
}
```

## `jax`

```bibtex
@software{jax,
  author = {James Bradbury and Roy Frostig and Peter Hawkins and Matthew James Johnson and Chris Leary and Dougal Maclaurin and George Necula and Adam Paszke and Jake Vander{P}las and Skye Wanderman-{M}ilne and Qiao Zhang},
  title = {{JAX}: composable transformations of {P}ython+{N}um{P}y programs},
  url = {http://github.com/google/jax},
  version = {0.3.13},
  year = {2018},
}
```


## `sympy`

```bibtex
@article{sympy,
     title = {SymPy: symbolic computing in Python},
     author = {Meurer, Aaron and Smith, Christopher P. and Paprocki, Mateusz and \v{C}ert\'{i}k, Ond\v{r}ej and Kirpichev, Sergey B. and Rocklin, Matthew and Kumar, AMiT and Ivanov, Sergiu and Moore, Jason K. and Singh, Sartaj and Rathnayake, Thilina and Vig, Sean and Granger, Brian E. and Muller, Richard P. and Bonazzi, Francesco and Gupta, Harsh and Vats, Shivam and Johansson, Fredrik and Pedregosa, Fabian and Curry, Matthew J. and Terrel, Andy R. and Rou\v{c}ka, \v{S}t\v{e}p\'{a}n and Saboo, Ashutosh and Fernando, Isuru and Kulal, Sumith and Cimrman, Robert and Scopatz, Anthony},
     year = 2017,
     month = jan,
     keywords = {Python, Computer algebra system, Symbolics},
     abstract = {
                SymPy is an open source computer algebra system written in pure Python. It is built with a focus on extensibility and ease of use, through both interactive and programmatic applications. These characteristics have led SymPy to become a popular symbolic library for the scientific Python ecosystem. This paper presents the architecture of SymPy, a description of its features, and a discussion of select submodules. The supplementary material provide additional examples and further outline details of the architecture and features of SymPy.
             },
     volume = 3,
     pages = {e103},
     journal = {PeerJ Computer Science},
     issn = {2376-5992},
     url = {https://doi.org/10.7717/peerj-cs.103},
     doi = {10.7717/peerj-cs.103}
}
```


## `tensorflow`
```bibtex
@INPROCEEDINGS{tensorflow,
  title={{Tensorflow: A system for large-scale machine learning}},
  author={Abadi, Mart{\'\i}n and Barham, Paul and Chen, Jianmin and Chen, Zhifeng and Davis, Andy and Dean, Jeffrey and Devin, Matthieu and Ghemawat, Sanjay and Irving, Geoffrey and Isard, Michael and others},
  booktitle={12th $\{$USENIX$\}$ Symposium on Operating Systems Design and Implementation ($\{$OSDI$\}$ 16)},
  pages={265--283},
  year={2016}
}
```

## `torch_geometric`
```bibtex
@INPROCEEDINGS{torch_geometric,
  title={Fast Graph Representation Learning with {PyTorch Geometric}},
  author={Fey, Matthias and Lenssen, Jan E.},
  booktitle={ICLR Workshop on Representation Learning on Graphs and Manifolds},
  year={2019},
}
```

## `astropy`
```bibtex
@ARTICLE{astropy,
       author = {{Astropy Collaboration} and {Price-Whelan}, Adrian M. and {Lim}, Pey Lian and {Earl}, Nicholas and {Starkman}, Nathaniel and {Bradley}, Larry and {Shupe}, David L. and {Patil}, Aarya A. and {Corrales}, Lia and {Brasseur}, C.~E. and {N{\"o}the}, Maximilian and {Donath}, Axel and {Tollerud}, Erik and {Morris}, Brett M. and {Ginsburg}, Adam and {Vaher}, Eero and {Weaver}, Benjamin A. and {Tocknell}, James and {Jamieson}, William and {van Kerkwijk}, Marten H. and {Robitaille}, Thomas P. and {Merry}, Bruce and {Bachetti}, Matteo and {G{\"u}nther}, H. Moritz and {Aldcroft}, Thomas L. and {Alvarado-Montes}, Jaime A. and {Archibald}, Anne M. and {B{\'o}di}, Attila and {Bapat}, Shreyas and {Barentsen}, Geert and {Baz{\'a}n}, Juanjo and {Biswas}, Manish and {Boquien}, M{\'e}d{\'e}ric and {Burke}, D.~J. and {Cara}, Daria and {Cara}, Mihai and {Conroy}, Kyle E. and {Conseil}, Simon and {Craig}, Matthew W. and {Cross}, Robert M. and {Cruz}, Kelle L. and {D'Eugenio}, Francesco and {Dencheva}, Nadia and {Devillepoix}, Hadrien A.~R. and {Dietrich}, J{\"o}rg P. and {Eigenbrot}, Arthur Davis and {Erben}, Thomas and {Ferreira}, Leonardo and {Foreman-Mackey}, Daniel and {Fox}, Ryan and {Freij}, Nabil and {Garg}, Suyog and {Geda}, Robel and {Glattly}, Lauren and {Gondhalekar}, Yash and {Gordon}, Karl D. and {Grant}, David and {Greenfield}, Perry and {Groener}, Austen M. and {Guest}, Steve and {Gurovich}, Sebastian and {Handberg}, Rasmus and {Hart}, Akeem and {Hatfield-Dodds}, Zac and {Homeier}, Derek and {Hosseinzadeh}, Griffin and {Jenness}, Tim and {Jones}, Craig K. and {Joseph}, Prajwel and {Kalmbach}, J. Bryce and {Karamehmetoglu}, Emir and {Ka{\l}uszy{\'n}ski}, Miko{\l}aj and {Kelley}, Michael S.~P. and {Kern}, Nicholas and {Kerzendorf}, Wolfgang E. and {Koch}, Eric W. and {Kulumani}, Shankar and {Lee}, Antony and {Ly}, Chun and {Ma}, Zhiyuan and {MacBride}, Conor and {Maljaars}, Jakob M. and {Muna}, Demitri and {Murphy}, N.~A. and {Norman}, Henrik and {O'Steen}, Richard and {Oman}, Kyle A. and {Pacifici}, Camilla and {Pascual}, Sergio and {Pascual-Granado}, J. and {Patil}, Rohit R. and {Perren}, Gabriel I. and {Pickering}, Timothy E. and {Rastogi}, Tanuj and {Roulston}, Benjamin R. and {Ryan}, Daniel F. and {Rykoff}, Eli S. and {Sabater}, Jose and {Sakurikar}, Parikshit and {Salgado}, Jes{\'u}s and {Sanghi}, Aniket and {Saunders}, Nicholas and {Savchenko}, Volodymyr and {Schwardt}, Ludwig and {Seifert-Eckert}, Michael and {Shih}, Albert Y. and {Jain}, Anany Shrey and {Shukla}, Gyanendra and {Sick}, Jonathan and {Simpson}, Chris and {Singanamalla}, Sudheesh and {Singer}, Leo P. and {Singhal}, Jaladh and {Sinha}, Manodeep and {Sip{\H{o}}cz}, Brigitta M. and {Spitler}, Lee R. and {Stansby}, David and {Streicher}, Ole and {{\v{S}}umak}, Jani and {Swinbank}, John D. and {Taranu}, Dan S. and {Tewary}, Nikita and {Tremblay}, Grant R. and {Val-Borro}, Miguel de and {Van Kooten}, Samuel J. and {Vasovi{\'c}}, Zlatan and {Verma}, Shresth and {de Miranda Cardoso}, Jos{\'e} Vin{\'\i}cius and {Williams}, Peter K.~G. and {Wilson}, Tom J. and {Winkel}, Benjamin and {Wood-Vasey}, W.~M. and {Xue}, Rui and {Yoachim}, Peter and {Zhang}, Chen and {Zonca}, Andrea and {Astropy Project Contributors}},
        title = "{The Astropy Project: Sustaining and Growing a Community-oriented Open-source Project and the Latest Major Release (v5.0) of the Core Package}",
      journal = {\apj},
     keywords = {Astronomy software, Open source software, Astronomy data analysis, 1855, 1866, 1858, Astrophysics - Instrumentation and Methods for Astrophysics},
         year = 2022,
        month = aug,
       volume = {935},
       number = {2},
          eid = {167},
        pages = {167},
          doi = {10.3847/1538-4357/ac7c74},
archivePrefix = {arXiv},
       eprint = {2206.14220},
 primaryClass = {astro-ph.IM},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2022ApJ...935..167A},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
```

## `xarray`
```bibtex
@ARTICLE{xarray,
  title     = {xarray: {N-D} labeled arrays and datasets in {Python}},
  author    = {Hoyer, S. and J. Hamman},
  journal   = {Journal of Open Research Software},
  volume    = {5},
  number    = {1},
  year      = {2017},
  publisher = {Ubiquity Press},
  doi       = {10.5334/jors.148},
  url       = {http://doi.org/10.5334/jors.148}
}
```

## `cartopy (0.18)`
```bibtex
@MISC{cartopy,
	title = {{SciTools}/cartopy: {Cartopy} 0.18.0},
	shorttitle = {{SciTools}/cartopy},
	url = {https://zenodo.org/record/3783894},
	abstract = {Major changes include: Support for building against Proj 6. Support for Python 3.7 and 3.8. Support for Matplotlib 3.2 and 3.3. Support for labelling gridlines on all projections. Support for labelling gridlines within plot boundaries instead of edges. Support for labelling of contours. and many others. There are several bug fixes as well. See the milestone for more information. Contributors @MBradbury @MarkWieczorek @QuLogic @ahuang11 @dopplershift @greglucas @htonchia @hugovk @kacmak7 @kaedonkers @ocefpaf @pelson @pharshalp @raphaelquast @sadielbartholomew @shevawen @snowman2 @stefraynaud @stephenworsley @wrongkindofdoctor @zbruick},
	urldate = {2020-07-14},
	publisher = {Zenodo},
	author = {Phil Elson and Elliott Sales de Andrade and Richard Hattersley and Ed Campbell and Ryan May and Andrew Dawson and Stephane Raynaud and Greg and scmc72 and Bill Little and Kevin Donkers and Byron Blay and Peter Killick and marqh and lbdreyer and Patrick Peglar and Nat Wilson and Jon Szymaniak and Andrew and Filipe and Corinne Bosley and Daniel Kirkham and Matthew Bradbury and Julia Signell and Mark Wieczorek and Lion Krischer and Hugo van Kemenade and htonchia and Daniel Eriksson and Andrea Smith},
	month = may,
	year = {2020},
	doi = {10.5281/zenodo.3783894},
}
```

## `pytorch_lightning`

```bibtex
@article{pytorch_lightning,
  title={PyTorch Lightning},
  author={Falcon, WA and .al},
  journal={GitHub. Note: https://github.com/PyTorchLightning/pytorch-lightning},
  volume={3},
  year={2019}
}
```

## `julia`

```bibtex
@article{julia,
  title = {Julia: {{A Fresh Approach}} to {{Numerical Computing}}},
  shorttitle = {Julia},
  author = {Bezanson, Jeff and Edelman, Alan and Karpinski, Stefan and Shah, Viral B.},
  year = {2015},
  month = jul,
  journal = {arXiv:1411.1607 [cs]},
  eprint = {1411.1607},
  eprinttype = {arxiv},
  primaryclass = {cs},
  abstract = {Bridging cultures that have often been distant, Julia combines expertise from the diverse fields of computer science and computational science to create a new approach to numerical computing. Julia is designed to be easy and fast. Julia questions notions generally held as "laws of nature" by practitioners of numerical computing: 1. High-level dynamic programs have to be slow. 2. One must prototype in one language and then rewrite in another language for speed or deployment, and 3. There are parts of a system for the programmer, and other parts best left untouched as they are built by the experts. We introduce the Julia programming language and its design --- a dance between specialization and abstraction. Specialization allows for custom treatment. Multiple dispatch, a technique from computer science, picks the right algorithm for the right circumstance. Abstraction, what good computation is really about, recognizes what remains the same after differences are stripped away. Abstractions in mathematics are captured as code through another technique from computer science, generic programming. Julia shows that one can have machine performance without sacrificing human convenience.},
  archiveprefix = {arXiv},
  keywords = {Computer Science - Mathematical Software},
}
```
