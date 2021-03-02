# Python citations
bibtex for various Python science and machine learning software.

Copy the contents of [main.bib](https://raw.githubusercontent.com/MilesCranmer/python_citations/master/main.bib) into your
bib file. Cite the packages with:
```latex
\cite{numpy,scipy,jupyter,sklearn,matplotlib,pandas,torch,tensorflow,torch_geometric,astropy,xarray,cartopy,pytorch_lightning}
```
(remove any you don't use).

Another format, indicating the name of the package in `\texttt` style, is as follows:
```latex
\texttt{numpy} \citep{numpy},
\texttt{scipy} \citep{scipy},
\texttt{jupyter} \citep{jupyter},
\texttt{sklearn} \citep{sklearn},
\texttt{matplotlib} \citep{matplotlib},
\texttt{pandas} \citep{pandas},
\texttt{torch} \citep{torch},
\texttt{tensorflow} \citep{tensorflow},
\texttt{torch\_geometric} \citep{torch_geometric},
\texttt{astropy} \citep{astropy},
\texttt{xarray} \citep{xarray},
\texttt{cartopy} \citep{cartopy},
\texttt{pytorch\_lightning} \citep{pytorch_lightning},
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
       author = {{Astropy Collaboration} and {Price-Whelan}, A.~M. and
         {Sip{\H{o}}cz}, B.~M. and {G{\"u}nther}, H.~M. and {Lim}, P.~L. and
         {Crawford}, S.~M. and {Conseil}, S. and {Shupe}, D.~L. and
         {Craig}, M.~W. and {Dencheva}, N. and {Ginsburg}, A. and {Vand
        erPlas}, J.~T. and {Bradley}, L.~D. and {P{\'e}rez-Su{\'a}rez}, D. and
         {de Val-Borro}, M. and {Aldcroft}, T.~L. and {Cruz}, K.~L. and
         {Robitaille}, T.~P. and {Tollerud}, E.~J. and {Ardelean}, C. and
         {Babej}, T. and {Bach}, Y.~P. and {Bachetti}, M. and {Bakanov}, A.~V. and
         {Bamford}, S.~P. and {Barentsen}, G. and {Barmby}, P. and
         {Baumbach}, A. and {Berry}, K.~L. and {Biscani}, F. and {Boquien}, M. and
         {Bostroem}, K.~A. and {Bouma}, L.~G. and {Brammer}, G.~B. and
         {Bray}, E.~M. and {Breytenbach}, H. and {Buddelmeijer}, H. and
         {Burke}, D.~J. and {Calderone}, G. and {Cano Rodr{\'\i}guez}, J.~L. and
         {Cara}, M. and {Cardoso}, J.~V.~M. and {Cheedella}, S. and {Copin}, Y. and
         {Corrales}, L. and {Crichton}, D. and {D'Avella}, D. and {Deil}, C. and
         {Depagne}, {\'E}. and {Dietrich}, J.~P. and {Donath}, A. and
         {Droettboom}, M. and {Earl}, N. and {Erben}, T. and {Fabbro}, S. and
         {Ferreira}, L.~A. and {Finethy}, T. and {Fox}, R.~T. and
         {Garrison}, L.~H. and {Gibbons}, S.~L.~J. and {Goldstein}, D.~A. and
         {Gommers}, R. and {Greco}, J.~P. and {Greenfield}, P. and
         {Groener}, A.~M. and {Grollier}, F. and {Hagen}, A. and {Hirst}, P. and
         {Homeier}, D. and {Horton}, A.~J. and {Hosseinzadeh}, G. and {Hu}, L. and
         {Hunkeler}, J.~S. and {Ivezi{\'c}}, {\v{Z}}. and {Jain}, A. and
         {Jenness}, T. and {Kanarek}, G. and {Kendrew}, S. and {Kern}, N.~S. and
         {Kerzendorf}, W.~E. and {Khvalko}, A. and {King}, J. and {Kirkby}, D. and
         {Kulkarni}, A.~M. and {Kumar}, A. and {Lee}, A. and {Lenz}, D. and
         {Littlefair}, S.~P. and {Ma}, Z. and {Macleod}, D.~M. and
         {Mastropietro}, M. and {McCully}, C. and {Montagnac}, S. and
         {Morris}, B.~M. and {Mueller}, M. and {Mumford}, S.~J. and {Muna}, D. and
         {Murphy}, N.~A. and {Nelson}, S. and {Nguyen}, G.~H. and
         {Ninan}, J.~P. and {N{\"o}the}, M. and {Ogaz}, S. and {Oh}, S. and
         {Parejko}, J.~K. and {Parley}, N. and {Pascual}, S. and {Patil}, R. and
         {Patil}, A.~A. and {Plunkett}, A.~L. and {Prochaska}, J.~X. and
         {Rastogi}, T. and {Reddy Janga}, V. and {Sabater}, J. and
         {Sakurikar}, P. and {Seifert}, M. and {Sherbert}, L.~E. and
         {Sherwood-Taylor}, H. and {Shih}, A.~Y. and {Sick}, J. and
         {Silbiger}, M.~T. and {Singanamalla}, S. and {Singer}, L.~P. and
         {Sladen}, P.~H. and {Sooley}, K.~A. and {Sornarajah}, S. and
         {Streicher}, O. and {Teuben}, P. and {Thomas}, S.~W. and
         {Tremblay}, G.~R. and {Turner}, J.~E.~H. and {Terr{\'o}n}, V. and
         {van Kerkwijk}, M.~H. and {de la Vega}, A. and {Watkins}, L.~L. and
         {Weaver}, B.~A. and {Whitmore}, J.~B. and {Woillez}, J. and
         {Zabalza}, V. and {Astropy Contributors}},
        title = "{The Astropy Project: Building an Open-science Project and Status of the v2.0 Core Package}",
      journal = {\aj},
     keywords = {methods: data analysis, methods: miscellaneous, methods: statistical, reference systems, Astrophysics - Instrumentation and Methods for Astrophysics},
         year = 2018,
        month = sep,
       volume = {156},
       number = {3},
          eid = {123},
        pages = {123},
          doi = {10.3847/1538-3881/aabc4f},
archivePrefix = {arXiv},
       eprint = {1801.02634},
 primaryClass = {astro-ph.IM},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2018AJ....156..123A},
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
