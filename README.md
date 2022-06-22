# TalkPython['Podcast'] Compilation of Notable PyPI Packages

👋 I love listening [Talk Python To Me Podcast](https://talkpython.fm/), a weekly podcast hosted by [Michael Kennedy](https://twitter.com/mkennedy) dedicated to the people and ideas in Python. The show covers a wide array of Python topics as well as many related topics (e.g. MongoDB, AngularJS, DevOps). He has a casual 45 minute conversation with industry experts. At the end of each episode, Michael asks two questions:

1. If you're going to write some Python code. What editor do you use?
2. Any notable PyPI (or Conda and sometimes npm) package?

This is a community & unofficial compilation of those amazing Notable PyPI (or Conda) Python Packages highligted at the end of the show.

Don't forget to hit the star ⭐ button if you like this project and would love to see updates.

## Thanks for sharing

Share this project on Twitter: <a href="https://twitter.com/intent/tweet?text=Check%20out%20this%20repo%20with%20great%20Python%20packages%20shared%20at%20@TalkPython%20with%20@mkennedy&url=https://github.com/xandrade/Talkpython.fm-Notable-Packages/&hashtags=Python,PyPi,TalkPython">![image](https://user-images.githubusercontent.com/12855744/167770565-0c8acce1-fe9d-440b-a93c-e57630a824c2.png)</a>

## Contribute
Pull requests welcome! Feature requests / bugs will be addressed through issues on this repository. While not every feature request will necessarily be handled by me, maintaining a record for interested contributors is useful.

Additionally, feel free to submit pull requests which add features or address bugs yourself.


# 2022


## [Episode 369](https://talkpython.fm/episodes/show/369/getting-lazy-with-python-imports-and-pep-690)

- Title: Getting Lazy with Python Imports and PEP 690
- Published Thu, Jun 16, 2022, recorded Fri, Jun 3, 2022.
- Guests: Carl Meyer on Twitter [@carljm](https://twitter.com/carljm) | Barry Warsaw on Twitter [@pumpichank](https://twitter.com/pumpichank) | Germán Méndez Bravo on Twitter [@germbravo](https://twitter.com/germbravo)

1. **Pyre** - *A performant type checker for Python.* [PyPi](https://pypi.org/project/pyre-check/) | [Website](https://pyre-check.org/) | [Source Code](https://github.com/facebook/pyre-check)

<img src="https://user-images.githubusercontent.com/12855744/174732165-f0646744-8639-42ff-b722-7282e542e68c.png" width="30%">

Pyre is a performant type checker for Python compliant with [PEP 484](https://peps.python.org/pep-0484/). Pyre can analyze codebases with millions of lines of code incrementally – providing instantaneous feedback to developers as they write code. You can try it out on examples in the Pyre Playground.

Pyre ships with Pysa, a security focused static analysis tool we've built on top of Pyre that reasons about data flows in Python applications. Please refer to our documentation to get started with our security analysis.

2. **μsort** - *A small, safe import sorter.* [PyPi](https://pypi.org/project/usort/) | [Website](https://usort.readthedocs.io/en/stable/) | [Source Code](https://github.com/facebookexperimental/usort)

μsort is a safe, minimal import sorter. Its primary goal is to make no "dangerous" changes to code. This is achieved by detecting distinct "blocks" of imports that are the most likely to be safely interchangeable, and only reordering imports within these blocks without altering formatting. Code style is left as an exercise for linters and formatters.

Within a block, µsort will follow common Python conventions for grouping imports based on source (standard library, third-party, first-party, or relative), and then sorting lexicographically within each group. 


3. **PDM** - *Python Development Master.* [PyPi](https://pypi.org/project/pdm/) | [Website](https://github.com/pdm-project/pdm) | [Source Code](https://github.com/pdm-project/pdm)

<img src="https://user-images.githubusercontent.com/12855744/174734382-2d01eccf-a0dc-45c2-8d88-0ffbdb85d2b1.png" width="40%">

PDM is meant to be a next generation Python package management tool. It was originally built for personal use. If you feel you are going well with Pipenv or Poetry and don't want to introduce another package manager, just stick to it. But if you are missing something that is not present in those tools, you can probably find some goodness in pdm.


## [Episode 368](https://talkpython.fm/episodes/show/368/end-to-end-web-testing-with-playwright)

- Title: End-to-End Web Testing with Playwright
- Published Fri, Jun 3, 2022, recorded Thu, May 12, 2022.
- Guest: Andrew Knight on Twitter [@AutomationPanda](https://twitter.com/AutomationPanda)

1. **Playwright** - *A high-level API to automate web browsers.* [PyPi](https://pypi.org/project/playwright/) | [Website](https://playwright.dev/) | [Source Code](https://github.com/microsoft/playwright)

<img src="https://user-images.githubusercontent.com/12855744/174730992-9c0917ed-10c4-430f-95f7-44b9ed2eb25e.png" width="15%">

Playwright is a Python library to automate Chromium, Firefox and WebKit browsers with a single API. Playwright delivers automation that is ever-green, capable, reliable and fast. See how Playwright is better.


## [Episode 367](https://talkpython.fm/episodes/show/367/say-hello-to-pyscript-webassembly-python)

- Title: Say Hello to PyScript (WebAssembly Python)
- Published Wed, May 25, 2022, recorded Thu, May 12, 2022.
- Guest: Fabio Pliger on Twitter [@b_smoke](https://twitter.com/b_smoke)

1. **Pyodide** - *A Python distribution for the browser and Node.js based on WebAssembly.* [PyPi](https://pypi.org/project/pyodide) | [Website](https://pyodide.org/en/stable/) | [Source Code](https://github.com/pyodide/pyodide)

<img src="https://user-images.githubusercontent.com/12855744/170831822-0978c2a6-a647-4c15-b48f-ff942a2d1e8f.png" width="50%">

Pyodide is a port of CPython to WebAssembly/Emscripten. It makes it possible to install and run Python packages in the browser with micropip. Any pure Python package with a wheel available on PyPI is supported. Many packages with C extensions have also been ported for use with Pyodide. These include many general-purpose packages such as regex, pyyaml, lxml and scientific Python packages including numpy, pandas, scipy, matplotlib, and scikit-learn.

Pyodide comes with a robust Javascript ⟺ Python foreign function interface so that you can freely mix these two languages in your code with minimal friction. This includes full support for error handling (throw an error in one language, catch it in the other), async/await, and much more.


## [Episode 366](https://talkpython.fm/episodes/show/366/optimizing-postgresql-db-queries-with-pgmustard)

- Title: Optimizing PostgreSQL DB Queries with pgMustard
- Published Fri, May 20, 2022, recorded Wed, May 11, 2022.
- Guest: Michael Christofides on Twitter [@michristofides](https://twitter.com/michristofides)

1. **arctype** - *SQL client and database management tool.* [Website](https://docs.arctype.com/)

<img src="https://user-images.githubusercontent.com/12855744/170832100-f5799033-6132-4861-a881-488244467895.png" width="50%">

Not a Python package, but a fast and easy-to-use SQL client for developers and teams.


## [Episode 365](https://talkpython.fm/episodes/show/365/solving-negative-engineering-problems-with-prefect)

- Title: Solving Negative Engineering Problems with Prefect
- Published Thu, May 12, 2022, recorded Mon, May 9, 2022.
- Guest: Chris White on Twitter [@markov_gainz](https://twitter.com/markov_gainz)

1. **rich** - *Render rich text, tables, progress bars, syntax highlighting, markdown and more to the terminal.* [PyPi](https://pypi.org/project/rich) | [Homepage](https://rich.readthedocs.io/en/latest/) | [Source Code](https://github.com/willmcgugan/rich)

<img src="https://user-images.githubusercontent.com/12855744/139004864-c8119f75-796f-45a1-8341-15db6e86caed.png" width="50%">

Rich is a Python library for rich text and beautiful formatting in the terminal. The Rich API makes it easy to add color and style to terminal output. Rich can also render pretty tables, progress bars, markdown, syntax highlighted source code, tracebacks, and more** - * out of the box. Hey, don't forget to try: ```from rich import print```, most welcome 😎

<img src="https://user-images.githubusercontent.com/12855744/139005130-c2b41766-f685-4aed-a763-6a12d3df05b2.png" width="50%">


2. **textual** - *Text User Interface using Rich.* [PyPi](https://pypi.org/project/textual/) | [Homepage](https://github.com/Textualize/textual) | [Source Code](https://github.com/Textualize/textual)

<img src="https://user-images.githubusercontent.com/12855744/168439274-fcde608f-9967-41eb-b37a-64916885e0f3.png" width="50%">

Textual is a TUI (Text User Interface) framework for Python inspired by modern web development. Currently a Work in Progress.


## [Episode 364](https://talkpython.fm/episodes/show/364/symbolic-math-with-python-using-sympy)

- Title: Symbolic Math with Python using SymPy
- Published Sat, May 7, 2022, recorded Fri, May 6, 2022.
- Guests: Aaron Meurer on Twitter [@asmeurer](https://twitter.com/asmeurer) | Ondrej Certik on Twitter [@OndrejCertik](https://twitter.com/OndrejCertik)

Package: **Hypothesis** - *Library for property-based testing.* [PyPi](https://pypi.org/project/hypothesis/) | [Website](https://hypothesis.works/) | [Source Code](https://github.com/HypothesisWorks/hypothesis)

<img src="https://user-images.githubusercontent.com/12855744/167633393-2777006d-bf87-4ba8-b4df-c1671b141383.png" width="50%">

`Hypothesis` is an advanced testing library for Python. It lets you write tests which are parametrized by a source of examples, and then generates simple and comprehensible examples that make your tests fail. This lets you find more bugs in your code with less work. Hypothesis is a powerful, flexible, and easy to use library for property-based testing.


## [Episode 363](https://talkpython.fm/episodes/show/363/python-for-.net-and-c-developers)

- Title: Python for .NET and C# developers
- Published Thu, Apr 28, 2022, recorded Wed, Apr 13, 2022.
- Guest: Cecil Phillip on Twitter [@cecilphillip](https://twitter.com/cecilphillip)

1. **scikit-learn** - *Simple and efficient tools for predictive data analysis.* [PyPi](https://pypi.org/project/scikit-learn/) | [Website](https://scikit-learn.org/stable/) | [Source Code](https://github.com/scikit-learn/scikit-learn)

<img src="https://user-images.githubusercontent.com/12855744/166110555-1931fa50-8efd-440b-8fd6-beb0dda54e2f.png" width="50%">

`scikit-learn` is a Python module for machine learning built on top of NumPy, SciPy, and matplotlib and is distributed under the 3-Clause BSD license (Open source & commercially usable). The project was started in 2007 by David Cournapeau as a Google Summer of Code project, and since then many volunteers have contributed. Simple and efficient tools for predictive data analysis


## [Episode 362](https://talkpython.fm/episodes/show/362/hypermodern-python-projects)

- Title: Hypermodern Python Projects
- Published Wed, Apr 20, 2022, recorded Wed, Apr 6, 2022.
- Guest: Claudio Jolowicz on Twitter [@cjolowicz](https://twitter.com/cjolowicz)

1. **Typeguard** - *Run-time type checker for Python.* [PyPi](https://pypi.org/project/typeguard/) | [Website](https://typeguard.readthedocs.io/en/latest/) | [Source Code](https://github.com/agronholm/typeguard)

<img src="https://user-images.githubusercontent.com/12855744/164708254-27f68b4e-b769-4072-93e2-efb87e99868d.png" width="50%">

`Typeguard` library provides run-time type checking for functions defined with PEP 484 argument (and return) type annotations.


## [Episode 361](https://talkpython.fm/episodes/show/361/pangeo-data-ecosystem)

- Title: Pangeo Data Ecosystem
- Published Sat, Apr 16, 2022, recorded Fri, Apr 1, 2022.
- Guests: Ryan Abernathey on Twitter [@rabernat](https://twitter.com/rabernat) | Joe Hamman on Twitter [@HammanHydro](https://twitter.com/HammanHydro)

1. **fsspec** - *Filesystem interfaces for Python.* [PyPi](https://pypi.org/project/fsspec/) | [Homepage](https://filesystem-spec.readthedocs.io/en/latest/) | [Source Code](https://github.com/intake/filesystem_spec)

Filesystem Spec (fsspec) is a project to provide a unified pythonic interface to local, remote and embedded file systems and bytes storage. As described, treat a remote database as a local file!

2. **pangeo-forge** - *Pipeline tools for building and publishing analysis ready datasets.* [PyPi](https://pypi.org/project/pangeo-forge/) | [Homepage](https://pangeo-forge.org/) | [Source Code](https://github.com/pangeo-forge/pangeo-forge-recipes)

<img src="https://user-images.githubusercontent.com/12855744/164237635-4209f14b-e1bd-4923-b16d-cae2d5b579a1.png" width="50%">

`Pangeo Forge` is an open source platform for data Extraction, Transformation, and Loading (ETL). The goal of Pangeo Forge is to make it easy to extract data from traditional data repositories and deposit in cloud object storage in analysis-ready, cloud-optimized (ARCO) format. Pangeo Forge is inspired directly by Conda Forge, a community-led collection of recipes for building conda packages. We hope that Pangeo Forge can play the same role for datasets.


## [Episode 360](https://talkpython.fm/episodes/show/360/removing-pythons-dead-batteries-in-just-5-years)

- Title: Removing Python's Dead Batteries (in just 5 years)
- Published Fri, Apr 8, 2022, recorded Tue, Mar 29, 2022.
- Guests: Brett Cannon [@brettsky](https://twitter.com/brettsky) | Christian Heimes [@ChristianHeimes](https://twitter.com/ChristianHeimes)


1. **wasmtime** - *A WebAssembly runtime powered by Wasmtime.* [PyPi](https://pypi.org/project/wasmtime/) | [Website](https://github.com/bytecodealliance/wasmtime-py) | [Source Code](https://github.com/bytecodealliance/wasmtime-py)

<img src="https://user-images.githubusercontent.com/12855744/163664940-d67cc08b-3f9f-4448-a270-17b49456d27f.png" width="50%">

`Wasmtime` is a standalone JIT-style runtime for WebAssembly, using Cranelift. This package is the WebAssembly runtime powered by Wasmtime.

2. **antigravity** - *A really simple module that allow everyone to do "import antigravity".* 

<img src="https://user-images.githubusercontent.com/12855744/163664890-3e9cf060-1767-40b6-a02a-301244e2d9b6.png" width="50%">

Some good reading here http://python-history.blogspot.com/2010/06/import-antigravity.html


## [Episode 359](https://talkpython.fm/episodes/show/359/lifecycle-of-a-machine-learning-project)

- Title: Lifecycle of a machine learning project
- Published Sun, Apr 3, 2022, recorded Tue, Mar 22, 2022.
- Guests: Demetrios on Twitter [@DPBrinkm](https://twitter.com/DPBrinkm) | Kate Kuznecova | Vishnu Rachakonda

<img src="https://user-images.githubusercontent.com/12855744/161989092-8b135695-9446-412d-bf8f-e0b698c2ec44.png" width="50%">

Great episode, but no time to share notable package. However, Kate shared a trick to run Jupyter Notebook like cells into any ```.py``` file in VSCode. For this, after instaling the Jupyter extension, you need to write ```# %%``` above the lines you would like to excecute. Right after, you can run the code as a cell. More infor [here](https://code.visualstudio.com/docs/python/jupyter-support-py).

## [Episode 358](https://talkpython.fm/episodes/show/358/understanding-pandas-visually-with-pandastutor)

- Title: Understanding Pandas visually with PandasTutor
- Published Fri, Mar 25, 2022, recorded Mon, Feb 28, 2022.
- Guest: Sam Lau on Twitter [@samlau95](https://twitter.com/samlau95)

1. **tqdm** - *Fast, Extensible Progress Meter.* [PyPi](https://pypi.org/project/tqdm) | [Website](https://tqdm.github.io/) | [Source Code](https://github.com/tqdm/tqdm)

<img src="https://user-images.githubusercontent.com/12855744/160227006-53093334-d953-4ed7-b39e-6ad352844433.png" width="50%">

`tqdm` derives from the Arabic word taqaddum (تقدّم) which can mean "progress," and is an abbreviation for "I love you so much" in Spanish (te quiero demasiado). Instantly make your loops show a smart progress meter - just wrap any iterable with tqdm(iterable), and you're done!


## [Episode 357](https://talkpython.fm/episodes/show/357/python-and-the-james-webb-space-telescope)

- Title: Python and the James Webb Space Telescope
- Published Mon, Mar 21, 2022, recorded Wed, Feb 23, 2022.
- Guest: JWST Scientists Megan Sosey and Mike Swam on [James Web Space Telescope](https://webbtelescope.org/)

1. **HTCondor** - *Distributed High Throughput Computing system API.* [PyPi](https://pypi.org/project/htcondor) | [Website](https://github.com/htcondor/htcondor/tree/latest) | [Source Code](https://github.com/htcondor/htcondor/)

<img src="https://user-images.githubusercontent.com/12855744/160227382-ceb6a136-ffd0-41c2-a59f-3a212634e330.png" width="50%">

`HTCondor` is a Distributed High Throughput Computing system developed at the Center for High Throughput Computing at the University of Wisconsin - Madison. With it, users can divide large computing workloads into jobs and submit them to an HTCondor scheduler, which will run them on worker nodes managed by HTCondor.

2. **Silly** - *A test data generator that generates stupid names.* [PyPi](https://pypi.org/project/silly) | [Website](https://github.com/cube-drone/silly) | [Source Code](https://github.com/cube-drone/silly)

A python library for producing fanciful test data. Like faker, but... silly


## [Episode 356](https://talkpython.fm/episodes/show/356/tips-for-ml-ai-startups)

- Title: Tips for ML / AI startups
- Published Mon, Mar 14, 2022, recorded Thu, Feb 17, 2022.
- Guest:  Dylan Fox on Twitter [@YouveGotFox](https://twitter.com/YouveGotFox)

1. **Hugging Face Hub** - *All the open source things related to huggingface.co.* [PyPi](https://pypi.org/project/huggingface-hub/) | [Website](https://huggingface.co) | [Source Code](https://github.com/huggingface/huggingface_hub)

<img src="https://user-images.githubusercontent.com/12855744/158339091-61110520-6070-46f3-a014-deb262dc4138.png" width="50%">

This library allows anyone to work with the Hub repositories: you can clone them, create them and upload your models to them. On top of this, the library also offers methods to access information from the Hub. For example, listing all models that meet specific criteria or get all the files from a specific repo. You can find the library implementation here.


## [Episode 355](https://talkpython.fm/episodes/show/355/edgedb-building-a-database-in-python)

- Title: EdgeDB - Building a database in Python
- Published Sun, Mar 6, 2022, recorded Wed, Feb 16, 2022.
- Guest: Yury Selivanov on Twitter [@1st1](https://twitter.com/@1st1) and [@edgedatabase](https://twitter.com/edgedatabase) 

1. **mypy** - *Static Typing for Python.* [PyPi](https://pypi.org/project/mypy/) | [Website](http://www.mypy-lang.org/) | [Source Code](https://github.com/python/mypy)

<img src="https://user-images.githubusercontent.com/12855744/156975442-3dcc247c-8205-4e36-b4fb-22d7a6d63474.png" width="50%">

`Mypy` is an optional static type checker for Python that aims to combine the benefits of dynamic (or "duck") typing and static typing. Mypy combines the expressive power and convenience of Python with a powerful type system and compile-time type checking. Mypy type checks standard Python programs; run them using any Python VM with basically no runtime overhead.


## [Episode 354](https://talkpython.fm/episodes/show/354/sphinx-myst-and-python-docs-in-2022)

- Title: Sphinx, MyST, and Python Docs in 2022
- Published Thu, Feb 24, 2022, recorded Wed, Jan 19, 2022.
- Guest: Panelists 

1. Pradyun Gedam on Twitter [@pradyunsg](https://twitter.com/pradyunsg)
2. Chris Holdgraf on Twitter [@choldgraf](https://twitter.com/choldgraf)
3. Paul Everitt on Twitter [@paulweveritt](https://twitter.com/paulweveritt)

1. **PursuedPyBear** - *An Event Driven Python Game Engine.* [PyPi](https://pypi.org/project/ppb/) | [Website](https://ppb.dev/) | [Source Code](https://github.com/ppb/pursuedpybear)

<img src="https://user-images.githubusercontent.com/12855744/155920736-bf431e9a-e37c-40b2-98d4-f8f659956c71.png" width="50%">

`PursuedPyBear`, also known as ppb, exists to be an educational resource. Most obviously used to teach computer science, it can be a useful tool for any topic that a simulation can be helpful. At its core, ppb provides a number of features that make it perfect for video games. The GameEngine itself provides a pluggable subsystem architecture where adding new features is as simple as subclassing and extending System. Additionally, it contains a state stack of Scenes simple containers that let you organize game scenes and UI screens in a simple way. Here is a [YouTube](https://www.youtube.com/watch?v=zM9G7wAf2g0 ) video from Casey Faist to show how fun PursuedPyBear could be at.

2. **Antidotes** - *Antidotes is a dependency injection micro-framework for Python 3.6+.* [PyPi](https://pypi.org/project/antidote/) | [Website](https://github.com/Finistere/antidote) | [Source Code](https://github.com/Finistere/antidote)

<img src="https://user-images.githubusercontent.com/12855744/155928632-00ea71d6-0058-4235-a725-8c94d6e6862e.png" width="50%">

It is built on the idea of ensuring best maintainability of your code while being as easy to use as possible. It also provides the fastest injection with @inject allowing you to use it virtually anywhere and fast full isolation of your tests.

3. **pipx** - *Install and Run Python Applications in Isolated Environments.* [PyPi](https://pypi.org/project/pipx) | [Homepage](https://pypa.github.io/pipx/) | [Source Code](https://github.com/pypa/pipx)

<img src="https://user-images.githubusercontent.com/12855744/136707633-b928adba-49d5-4068-88e2-92c16462381a.png" width="40%">

This is one of the episodes with the most of packages described. Therefore, we picked the one with the best logo 😃: `pipx`. This is a tool to help you install and run end-user applications written in Python. It's roughly similar to macOS's brew, JavaScript's npx, and Linux's apt.


## [Episode 353](https://talkpython.fm/episodes/show/353/sqlmodel-the-new-orm-for-fastapi-and-beyond)

- Title: SQLModel: The New ORM for FastAPI and Beyond
- Published Fri, Feb 18, 2022, recorded Mon, Jan 17, 2022.
- Guest: Sebastián Ramírez on Twitter [@tiangolo](https://twitter.com/tiangolo)

1. **ODMantic** - *Asynchronous ODM (Object Document Mapper) for MongoDB.* [PyPi](https://pypi.org/project/odmantic) | [Website](https://art049.github.io/odmantic/) | [Source Code](https://github.com/art049/odmantic)

<img src="https://user-images.githubusercontent.com/12855744/155114239-0d1cc92a-c935-41c1-ba85-065749309eb9.png" width="50%">

Asynchronous ODM (Object Document Mapper) for MongoDB based on standard python type hints. It's built on top of pydantic for model definition and validation.

2. **Beanie** - *Asynchronous Python object-document mapper (ODM) for MongoDB.* [PyPi](https://pypi.org/project/beanie) | [Website](https://github.com/roman-right/beanie) | [Source Code](https://github.com/roman-right/beanie)

<img src="https://user-images.githubusercontent.com/12855744/155114604-6a652c73-deb3-4e80-ab67-2524665fc2d4.png" width="50%">

Asynchronous Python object-document mapper (ODM) for MongoDB, based on Motor and Pydantic.

## [Episode 352](https://talkpython.fm/episodes/show/352/running-python-in-production)

- Title: Running Python in Production
- Published Tue, Feb 8, 2022, recorded Wed, Jan 12, 2022.
- Guests: 
1. Emily Morehouse-Valcarcel on Twitter [@emilyemorehouse](https://twitter.com/emilyemorehouse)
2. Hynek Schlawack on Twitter [@hynek](https://twitter.com/hynek)
3. Glyph on Twitter [@glyph](https://twitter.com/glyph)

There was no time for notable PiPy packages, but it is another great eposide to listen!

## [Episode 351](https://talkpython.fm/episodes/show/351/machine-learning-ethics-and-laws-panel)

- Title: Machine Learning Ethics and Laws Panel
- Published Thu, Feb 3, 2022, recorded Fri, Dec 17, 2021.
- Guests: 
1. Emily Morehouse-Valcarcel on Twitter [@kjam](https://twitter.com/kjam)
2. Hynek Schlawack on Twitter [@_inesmontani](https://twitter.com/_inesmontani)

There was no time for notable PiPy packages, but it is a great eposide to listen!

## [Episode 350](https://talkpython.fm/episodes/show/350/python-steering-council-2021-retrospective)

- Title: Python Steering Council 2021 Retrospective
- Published Wed, Jan 26, 2022, recorded Tue, Dec 14, 2021.
- Guests: 
1. Barry Warsaw on Twitter [@pumpichank](https://twitter.com/pumpichank)
2. Carol Willing on Twitter [@WillingCarol](https://twitter.com/WillingCarol)
3. Brett Cannon on Twitter [@brettsky](https://twitter.com/brettsky)
4. Pablo Galindo Salgado on Twitter [@pyblogsal](https://twitter.com/pyblogsal) 
5. T. Wouters on Twitter [@Yhg1s](https://twitter.com/Yhg1s)

There was no time for notable PiPy packages, but it was a great show & must listen episode with the Python Steering Council Members!


## [Episode 349](https://talkpython.fm/episodes/show/349/meet-beanie-a-mongodb-odm-pydantic)

- Title: Meet Beanie: A MongoDB ODM + Pydantic
- Published Sat, Jan 22, 2022, recorded Thu, Nov 18, 2021.
- Guest: Roman Right on Tweeter [@roman_the_right](https://twitter.com/roman_the_right)

1. **Yarl** - *Yet another URL library.* [PyPi](https://pypi.org/project/Yarl) | [Website](https://yarl.readthedocs.io/en/latest/) | [Source Code](https://github.com/aio-libs/yarl/)

<img src="https://user-images.githubusercontent.com/12855744/150691879-e9d1276a-9c7b-4c40-8d56-d2b97003e4d5.png" width="50%">

The module provides handy URL class for URL parsing and changing.


## [Episode 348](https://talkpython.fm/episodes/show/348/dear-pygui-simple-yet-fast-python-gui-apps)

- Title: Dear PyGui: Simple yet Fast Python GUI Apps
- Published Mon, Jan 17, 2022, recorded Tue, Nov 9, 2021.
- Guestes: Jonathan Hoffstadt on Tweeter [@jhoffs1](https://twitter.com/jhoffs1) | Preston Cothren on Tweeter [@toulaboy3](https://twitter.com/toulaboy3)

1. **NumPy** - *Fundamental package for array computing with Python..* [PyPi](https://pypi.org/project/NumPy) | [Website](https://numpy.org/) | [Source Code](https://github.com/numpy/numpy)

<img src="https://user-images.githubusercontent.com/12855744/149876499-3dbf1b8f-6cd2-430a-89d5-b6cf6d211e2a.png" width="30%">

- POWERFUL N-DIMENSIONAL ARRAYS Fast and versatile, the NumPy vectorization, indexing, and broadcasting concepts are the de-facto standards of array computing today.
- NUMERICAL COMPUTING TOOLS NumPy offers comprehensive mathematical functions, random number generators, linear algebra routines, Fourier transforms, and more.
- INTEROPERABLE NumPy supports a wide range of hardware and computing platforms, and plays well with distributed, GPU, and sparse array libraries.
- PERFORMANT The core of NumPy is well-optimized C code. Enjoy the flexibility of Python with the speed of compiled code.
- EASY TO USE NumPy’s high level syntax makes it accessible and productive for programmers from any background or experience level.
- OPEN SOURCE Distributed under a liberal BSD license, NumPy is developed and maintained publicly on GitHub by a vibrant, responsive, and diverse community.


## [Episode 347](https://talkpython.fm/episodes/show/347/cinder-specialized-python-that-flies)

- Title: Cinder - Specialized Python that Flies
- Published Sat, Jan 8, 2022, recorded Mon, Nov 29, 2021.
- Guest: Dino Viehland on Tweeter [@DinoViehland](https://twitter.com/DinoViehland)

1. **mock** - *Test tools for mocking and patching.* [PyPi](https://pypi.org/project/mock) | [Website](https://docs.python.org/3/library/unittest.mock.html) | [Source Code](https://github.com/python/cpython/blob/3.10/Lib/unittest/mock.py)

`mock` is a library for testing in Python. It allows you to replace parts of your system under test with mock objects and make assertions about how they have been used. Spoiler alert, mock is now part of the Python standard library, available as unittest.mock in Python 3.3 onwards. This package contains a rolling backport of the standard library mock code compatible with Python 3.6 and up. unittest.mock is a library for testing in Python. It allows you to replace parts of your system under test with mock objects and make assertions about how they have been used. unittest.mock provides a core Mock class removing the need to create a host of stubs throughout your test suite. After performing an action, you can make assertions about which methods / attributes were used and arguments they were called with. You can also specify return values and set needed attributes in the normal way.


# 2021

## [Episode 346](https://talkpython.fm/episodes/show/346/20-recommended-packages-in-review)

- Title: 20 Recommended Packages in Review
- Published Tue, Dec 21, 2021, recorded Wed, Nov 24, 2021.
- Guest: Antonio Andrade [@AntonioAndrade](https://twitter.com/AntonioAndrade) | [LinkedIn](https://www.linkedin.com/in/antonioxandrade/) <- *Hey, Mom! Michael invited me to the podcast 😁*


1. **Sumy** - *Module for automatic summarization of text documents and HTML pages.* [PyPi](https://pypi.org/project/sumy) | [Website](https://github.com/miso-belica/sumy) | [Source Code](https://github.com/miso-belica/sumy)

<img src="https://user-images.githubusercontent.com/12855744/146977953-315f2aba-63f8-462c-9ff0-b7146656b907.png" width="50%">

Simple library and command line utility for extracting summary from HTML pages or plain texts. The package also contains simple evaluation framework for text summaries. Implemented summarization methods are described in the documentation. I also maintain a list of alternative implementations of the summarizers in various programming languages.


2. **gTTS** - *Python library and CLI tool to interface with Google Translate text-to-speech API.* [PyPi](https://pypi.org/project/gTTS) | [Website](http://gtts.readthedocs.org/) | [Source Code](https://github.com/pndurette/gTTS)

<img src="https://user-images.githubusercontent.com/12855744/146977895-947d86f2-ba84-43b4-bb88-2c0b7240abbb.png" width="50%">

gTTS (Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate's text-to-speech API. Write spoken mp3 data to a file, a file-like object (bytestring) for further audio manipulation, or stdout. Or simply pre-generate Google Translate TTS request URLs to feed to an external program. 


## [Episode 345](https://talkpython.fm/episodes/show/345/10-tips-and-tools-for-developer-productivity)

- Title: 10 Tips and Tools for Developer Productivity
- Published Wed, Dec 15, 2021, recorded Wed, Nov 17, 2021.
- Guest: Jay Miller [@kjaymiller](https://twitter.com/kjaymiller)

1. **Black** - *The uncompromising code formatter.* [PyPi](https://pypi.org/project/black/) | [Homepage](https://github.com/psf/black/) | [Source Code](https://github.com/psf/black)

<img src="https://user-images.githubusercontent.com/12855744/134875262-4c0059f8-365c-4df7-8c12-d48e389fa1a6.png" width="50%">

`Black` is the uncompromising Python code formatter. By using it, you agree to cede control over minutiae of hand-formatting. In return, Black gives you speed, determinism, and freedom from pycodestyle nagging about formatting. You will save time and mental energy for more important matters. We all love Black!

2. **rumps** - *Ridiculously Uncomplicated macOS Python Statusbar apps.* [PyPi](https://pypi.org/project/rumps) | [Website](https://github.com/jaredks/rumps) | [Source Code](https://github.com/jaredks/rumps)

<img src="https://user-images.githubusercontent.com/12855744/146977086-19b24666-040f-4347-9239-09ccdad5b866.png" width="50%">

`rumps` (Ridiculously Uncomplicated macOS Python Statusbar apps) can greatly shorten the code required to generate a working app. No PyObjC underscore syntax required!. rumps is for any console-based program that would benefit from a simple configuration toolbar or launch menu.


## [Episode 344](https://talkpython.fm/episodes/show/344/sqlalchemy-2.0)

- Title: SQLAlchemy 2.0
- Published Thu, Dec 9, 2021, recorded Wed, Nov 10, 2021.
- Guest: Mike Bayer [@zzzeek](https://twitter.com/zzzeek)

1. **nplusone** - *Detecting the n+1 queries problem in Python.* [PyPi](https://pypi.org/project/nplusone) | [Website](https://github.com/jmcarp/nplusone) | [Source Code](https://github.com/jmcarp/nplusone)

nplusone is a library for detecting the n+1 queries problem in Python ORMs, including SQLAlchemy, Peewee, and the Django ORM.


## [Episode 343](https://talkpython.fm/episodes/show/343/do-excel-things-get-notebook-python-code-with-mito)

- Title: Do Excel things, get notebook Python code with Mito
- Published Tue, Nov 30, 2021, recorded Mon, Nov 8, 2021.
- Guest: Panelists (🆘🙋 HELP WANTED! to update names and social media links)

1. **Pandas Profiling** - *Generate profile report for pandas DataFrame.* [PyPi](https://pypi.org/project/pandas-profiling/) | [Website](https://pandas-profiling.github.io/pandas-profiling/) | [Source Code](https://github.com/pandas-profiling/pandas-profiling)

<img src="https://user-images.githubusercontent.com/12855744/144227540-1837cd2e-df5b-44e8-a9db-c8f858f27978.png" width="80%">

Generates profile reports from a pandas DataFrame. The pandas df.describe() function is great but a little basic for serious exploratory data analysis. `pandas_profiling` extends the pandas DataFrame with df.profile_report() for quick data analysis. I'm a heavy user of this library, thanks for existing!


## [Episode 342](https://talkpython.fm/episodes/show/342/python-in-architecture-as-in-actual-buildings)

- Title: Python in Architecture (as in actual buildings)
- Published Tue, Nov 23, 2021, recorded Sun, Nov 7, 2021.
- Guest: Gui Talarico on [GitHub](https://github.com/gtalarico/gtalarico)

1. **Pythonic** - *Graphical automation tool.* [PyPi](https://pypi.org/project/pythonic) | [Website](https://github.com/hANSIc99/Pythonic) | [Source Code](https://github.com/hANSIc99/Pythonic)

<img src="https://user-images.githubusercontent.com/12855744/143287362-d8c7d821-c983-493f-8c1c-5382279cde3e.png" width="50%">

`Pythonic` is a graphical programming tool that makes it easy for users to create Python applications using ready-made function modules.


## [Episode 341](https://talkpython.fm/episodes/show/341/25-pandas-functions-you-didn-t-know-existed)

- Title: 25 Pandas Functions You Didn’t Know Existed
- Published Wed, Nov 17, 2021, recorded Thu, Nov 4, 2021.
- Guest: Bex Tuychiev [LinkedIn](https://www.linkedin.com/in/bextuychiev/)

1. **umap-learn** - *Uniform Manifold Approximation and Projection.* [PyPi](https://pypi.org/project/umap-learn) | [Website](https://umap-learn.readthedocs.io/en/latest/) | [Source Code](https://github.com/lmcinnes/umap)

<img src="https://user-images.githubusercontent.com/12855744/142350425-db878216-b091-49c4-920a-0288dbc7f90d.png" width="50%">

Working with data and searching for a low dimensional projection that has the closest possible equivalent fuzzy topological structure? Uniform Manifold Approximation and Projection (UMAP) is a dimension reduction technique that can be used for visualisation similarly to t-SNE, but also for general non-linear dimension reduction. 


## [Episode 340](https://talkpython.fm/episodes/show/340/time-to-jit-your-python-with-pyjion)

- Title: Time to JIT your Python with Pyjion?
- Published Wed, Nov 10, 2021, recorded Wed, Nov 3, 2021.
- Guest: Anthony Shaw [@anthonypjshaw](https://twitter.com/anthonypjshaw)

1. **Tortoise ORM** - *Easy async ORM for python, built with relations in mind.* [PyPi](https://pypi.org/project/tortoise-orm/) | [Website](https://tortoise.github.io/) | [Source Code](https://github.com/tortoise/tortoise-orm)

<img src="https://user-images.githubusercontent.com/12855744/141423182-bc3b661f-b0b2-42ed-8609-c7ac80ce7ce1.png" width="50%">

`Tortoise ORM` is an easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django. Tortoise ORM was built with relations in mind and admiration for the excellent and popular Django ORM. It’s engraved in its design that you are working not with just tables, you work with relational data.

2. **Beanie** - *Asynchronous Python ODM for MongoDB.* [PyPi](https://pypi.org/project/Beanie/) | [Website](https://roman-right.github.io/beanie/) | [Source Code](https://github.com/roman-right/beanie)

![image](https://user-images.githubusercontent.com/12855744/141423414-a7527a59-6d8b-4f00-964b-17136ea635d0.png)

`Beanie` is an Asynchronous Python object-document mapper (ODM) for MongoDB, based on Motor and Pydantic. When using Beanie each database collection has a corresponding Document that is used to interact with that collection. In addition to retrieving data, Beanie allows you to add, update, or delete documents from the collection as well.

3. **Hathi** - *SQL host scanner and dictionary attack tool* [PyPi](https://pypi.org/project/hathi/) | [Website](https://github.com/tonybaloney/hathi) | [Source Code](https://github.com/tonybaloney/hathi)

<img src="https://user-images.githubusercontent.com/12855744/141425986-51c92b3b-9771-4467-96ca-1114c9f1ebe6.png" width="50%">

A SQL host scanner and dictionary attack tool. Comes with a script (`filter_pass.py`) to filter a series of password lists based on password strength.


## [Episode 339](https://talkpython.fm/episodes/show/339/making-python-faster-with-guido-and-mark)

- Title: Making Python Faster with Guido and Mark
- Published Thu, Nov 4, 2021, recorded Mon, Nov 1, 2021.
- Guests: Guido van Rossum [@gvanrossum](https://twitter.com/gvanrossum) | Mark Shannon [LinkedIn](https://www.linkedin.com/in/mark-shannon-bb459551/)

No notable package was mentioned during this episode, but we appreciate the ongoing work for making Python faster (one step at the time).


## [Episode 338](https://talkpython.fm/episodes/show/338/using-cibuildwheel-to-manage-the-scikit-hep-packages)

- Title: Using cibuildwheel to manage the scikit-HEP packages
- Published Sun, Oct 17, 2021, recorded Thu, Oct 14, 2021.
- Guest: Henry Schreiner [@HenrySchreiner3](https://twitter.com/HenrySchreiner3)

1. **plotext** - *Plots data directly on terminal.* [PyPi](https://pypi.org/project/plotext/) | [Homepage](https://github.com/piccolomo/plotext) | [Source Code](https://github.com/piccolomo/plotext)

![image](https://user-images.githubusercontent.com/12855744/138847569-abd614dd-1886-496b-a5ff-6696ca0b796b.png)

CLI lovers 📣, plotext plots directly on terminal, it has no dependencies and the syntax is very similar to matplotlib. It also provides a simple command line tool.


## [Episode 337](https://talkpython.fm/episodes/show/337/kedro-for-maintainable-data-science)

- Title: Kedro for Maintainable Data Science
- Published Sat, Oct 9, 2021, recorded Fri, Oct 1, 2021.
- Guests: Waylon Walker [@_WaylonWalker](https://twitter.com/_WaylonWalker) | Yetunde Dada [@yetudada](https://twitter.com/yetudada) | Ivan Danov [@ivandanov](https://twitter.com/ivandanov)

1. **fsspec** - *Filesystem interfaces for Python.* [PyPi](https://pypi.org/project/fsspec/) | [Homepage](https://filesystem-spec.readthedocs.io/en/latest/) | [Source Code](https://github.com/intake/filesystem_spec)

Filesystem Spec (fsspec) is a project to provide a unified pythonic interface to local, remote and embedded file systems and bytes storage. As described, treat a remote database as a local file!

2. **Dynaconf** - *Configuration Management for Python.* [PyPi](https://pypi.org/project/dynaconf/) | [Homepage](https://www.dynaconf.com/) | [Source Code](https://github.com/rochacbruno/dynaconf)

![image](https://user-images.githubusercontent.com/12855744/136692271-889f25bf-8040-4fd8-a49e-e8741b1e77f8.png)

 Lazy setting loader on steroids!
 

## [Episode 336](https://talkpython.fm/episodes/show/336/terminal-magic-with-rich-and-textual)

- Title: Terminal magic with Rich and Textual
- Published: Tue, Oct 5, 2021, recorded Mon, Sep 27, 2021.
- Guest: Will McGugan [@willmcgugan](https://twitter.com/willmcgugan)

1. **Objexplore** - *Interactive Python Object Explorer.* [PyPi](https://pypi.org/project/objexplore/) | [Homepage](https://github.com/kylepollina/objexplore) | [Source Code](https://github.com/kylepollina/objexplore)

<img src="https://user-images.githubusercontent.com/12855744/136142250-6f3e7688-ff1e-47cd-8377-a5e50e2a3388.png" width="50%">

 `Objexplore` is an interactive Python object explorer for the terminal. Use it while debugging, or exploring a new library, or whatever!

 
## [Episode 335](https://talkpython.fm/episodes/show/335/gene-editing-with-python)

- Title: Gene Editing with Python
- Published Fri, Sep 24, 2021, recorded Wed, Sep 15, 2021.
- Guest: David Born [@Hypostulate](https://twitter.com/Hypostulate) | [Beam Therapeutics](https://beamtx.com)

1. **AWS Cloud Development Kit (AWS CDK)**. [PyPi](https://pypi.org/project/aws-cdk.core/) | [Homepage](https://docs.aws.amazon.com/cdk/latest/guide/work-with-cdk-python.html) | [Source Code](https://github.com/aws/aws-cdk)

![image](https://user-images.githubusercontent.com/12855744/134805873-f9d79c4b-915e-4460-8759-b739a5e72001.png)

The `AWS Cloud Development Kit` (AWS CDK) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation.

2. **Luigi** - *Workflow mgmgt + task scheduling + dependency resolution.* [PyPi](https://pypi.org/project/luigi/) | [Homepage](https://github.com/spotify/luigi) | [Source Code](https://github.com/spotify/luigi)

![image](https://user-images.githubusercontent.com/12855744/134805722-335e5512-e432-4f43-8b26-3946f5e95496.png)

Luigi is a Python (3.6, 3.7, 3.8, 3.9 tested) package that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization, handling failures, command line integration, and much more.


## [Episode 334](https://talkpython.fm/episodes/show/334/microsoft-planetary-computer)

- Title: Microsoft Planetary Computer
- Published Sat, Sep 18, 2021, recorded Thu, Sep 9, 2021.
- Guests: Rob Emanuele [@lossyrob](https://twitter.com/lossyrob) | Tom Augspurger [@TomAugspurger](https://twitter.com/TomAugspurger)

1. **Seaborn** - *Statistical Data Visualization.* [PyPi](https://pypi.org/project/seaborn/) | [Homepage](https://seaborn.pydata.org/) | [Source Code](https://github.com/cupy/cupy/)

<img src="https://user-images.githubusercontent.com/12855744/134805244-6561b2e6-9b00-442c-b125-3edd347677ff.png" width="50%">

Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics. If matplotlib is for Android users, seaborn is for iPhone users!


## [Episode 333](https://talkpython.fm/episodes/show/333/state-of-data-science-in-2021)

- Title: State of Data Science in 2021 
- Published Fri, Sep 10, 2021, recorded Thu, Sep 9, 2021
- Guest: Stan Seibert [@seibert](https://twitter.com/seibert) 

1. **CuPy** - *NumPy & SciPy for GPU.* [PyPi](https://pypi.org/project/cupy/) | [Homepage](https://cupy.dev/) | [Source Code](https://github.com/cupy/cupy/)

<img src="https://user-images.githubusercontent.com/12855744/134486395-6af8b913-9c0b-40f4-9c95-5c51ed44cf53.png" width="50%">

CuPy is an open-source array library for GPU-accelerated computing with Python. CuPy utilizes CUDA Toolkit libraries including cuBLAS, cuRAND, cuSOLVER, cuSPARSE, cuFFT, cuDNN and NCCL to make full use of the GPU architecture. Basically, NumPy & SciPy on steroids! 


## [Episode 332](https://talkpython.fm/episodes/show/332/robust-python)


- Title: Robust Python
- Published Tue, Aug 31, 2021, recorded Mon, Aug 30, 2021.
- Guest: Patrick Viafore [@PatViaforever](https://twitter.com/PatViaforever) 

1. **Stevedore** - *Manage dynamic plugins for Python applications.* [PyPi](https://pypi.org/project/stevedore/) | [Homepage](https://docs.openstack.org/stevedore/latest/) | [Source Code](https://opendev.org/openstack/stevedore)

Python makes loading code dynamically easy, allowing you to configure and extend your application by discovering and loading extensions ("plugins") at runtime. Many applications implement their own library for doing this, using __import__ or importlib. Stevedore avoids creating yet another extension mechanism by building on top of setuptools entry points. The code for managing entry points tends to be repetitive, though, so stevedore provides manager classes for implementing common patterns for using dynamically loaded extensions.


## [Episode 331](https://talkpython.fm/episodes/show/331/meet-the-python-developer-in-residence-lukasz-langa)

- Title: Meet the Python Developer in Residence: Lukasz Langa
- Published Fri, Aug 27, 2021, recorded Wed, Aug 25, 2021.
- Guest: Łukasz Langa [@llanga](https://twitter.com/llanga) 

The question was not asked, but since Łukasz is the author of Black... here we go!

1. **Black** - *The uncompromising code formatter.* [PyPi](https://pypi.org/project/black/) | [Homepage](https://github.com/psf/black/) | [Source Code](https://github.com/psf/black)

<img src="https://user-images.githubusercontent.com/12855744/134875262-4c0059f8-365c-4df7-8c12-d48e389fa1a6.png" width="50%">

Black is the uncompromising Python code formatter. By using it, you agree to cede control over minutiae of hand-formatting. In return, Black gives you speed, determinism, and freedom from pycodestyle nagging about formatting. You will save time and mental energy for more important matters. We all love Black!


## [Episode 330](https://talkpython.fm/episodes/show/330/apache-airflow-open-source-workflow-with-python)

- Title: Apache Airflow Open-Source Workflow with Python
- Published Fri, Aug 20, 2021, recorded Thu, Aug 5, 2021.
- Guests: Jarek Potiuk [LinkedIn](https://www.linkedin.com/in/jarekpotiuk/) | Kaxil Naik [@kaxil](https://twitter.com/kaxil) | Leah Cole [@leahecole](https://twitter.com/leahecole)

The question was not asked, but since the team talked about Airflow..

1. **Apache Airflow** - *Programmatically author, schedule and monitor data pipelines.* [PyPi](https://pypi.org/project/apache-airflow/) | [Homepage](https://airflow.apache.org/) | [Source Code](https://github.com/apache/airflow)

<img src="https://user-images.githubusercontent.com/12855744/134873876-146ad757-d8e1-4b80-8b85-7a99dcfb43c4.png" width="50%">

Airflow is a platform created by the community to programmatically author, schedule and monitor workflows. Airflow works best with workflows that are mostly static and slowly changing. When the DAG structure is similar from one run to the next, it clarifies the unit of work and continuity. Other similar projects include Luigi, Oozie and Azkaban.

Airflow is commonly used to process data, but has the opinion that tasks should ideally be idempotent (i.e., results of the task will be the same, and will not create duplicated data in a destination system), and should not pass large quantities of data from one task to the next (though tasks can pass metadata using Airflow's Xcom feature). For high-volume, data-intensive tasks, a best practice is to delegate to external services specializing in that type of work.


## [Episode 329](https://talkpython.fm/episodes/show/329/geekout-renewable-energy)

- Title: Geekout: Renewable Energy
- Published Fri, Aug 13, 2021, recorded Wed, Aug 4, 2021.
- Guest: Richard Campbell [@richcampbell](https://twitter.com/richcampbell)


No time for this question :-(


## [Episode 328](https://talkpython.fm/episodes/show/328/piccolo-a-fast-async-orm-for-python-updated)

- Title: Piccolo: A fast, async ORM for Python (updated)
- Published Sun, Aug 8, 2021, recorded Thu, Jul 22, 2021.
- Guest: Daniel Townsend [@danieltownsend](https://twitter.com/danieltownsend)


1. **Pydantic** - *Data validation and settings management.* [PyPi](https://pypi.org/project/pydantic/) | [Homepage](https://github.com/samuelcolvin/pydantic) | [Source Code](https://github.com/samuelcolvin/pydantic)

<img src="https://user-images.githubusercontent.com/12855744/135242282-48d99135-f02e-4421-baec-4d8ff674dd51.png" width="50%">

Fast and extensible, pydantic plays nicely with your linters/IDE/brain. Define how data should be in pure, canonical Python 3.6+; validate it with pydantic.


## [Episode 327](https://talkpython.fm/episodes/show/327/little-automation-tools-in-python)

- Title: Little Automation Tools in Python
- Published Fri, Jul 30, 2021, recorded Thu, Jul 15, 2021.
- Guests: Rivers Cuomo [@RiversCuomo](https://twitter.com/RiversCuomo) | Jay Miller [@kjaymiller](https://twitter.com/kjaymiller) | Kim van Wyk [@kim_vanwyk](https://twitter.com/kim_vanwyk) | Rusti Gregory [@greenermountain](https://twitter.com/greenermountain)

1. **pipx** - *Install and Run Python Applications in Isolated Environments.* [PyPi](https://pypi.org/project/pipx) | [Homepage](https://pypa.github.io/pipx/) | [Source Code](https://github.com/pypa/pipx)

<img src="https://user-images.githubusercontent.com/12855744/136707633-b928adba-49d5-4068-88e2-92c16462381a.png" width="50%">

This is one of the episodes with the most of packages described. Therefore, we picked the one with the best logo 😃: **pipx**. This is a tool to help you install and run end-user applications written in Python. It's roughly similar to macOS's brew, JavaScript's npx, and Linux's apt.



## [Episode 326](https://talkpython.fm/episodes/show/326/building-desktop-apps-with-wxpython)

- Title: Building Desktop Apps with wxPython
- Published Fri, Jul 23, 2021, recorded Wed, Jul 14, 2021.
- Guest: Mike Driscoll [@driscollis](https://twitter.com/driscollis)

1. **openpyxl** - *A Python library to read/write Excel 2010 xlsx/xlsm files.* [PyPi](https://pypi.org/project/openpyxl) | [Homepage](https://openpyxl.readthedocs.io/en/stable/) | [Source Code](https://foss.heptapod.net/openpyxl/openpyxl)

<img src="https://user-images.githubusercontent.com/12855744/139002636-d2a4c87a-ac15-408e-956b-c65888cd9356.png" width="50%">



## [Episode 325](https://talkpython.fm/episodes/show/325/micropython-circuitpython)

- Title: MicroPython + CircuitPython
- Published Thu, Jul 15, 2021, recorded Thu, Jul 8, 2021.
- Guests: Scott [@tannewt](https://twitter.com/tannewt) | Damien's [Site](https://dpgeorge.net)

1. **HttpPy** - *More comfortable requests with python.* [PyPi](https://pypi.org/project/HttpPy/) | [Homepage](https://github.com/everitosan/HttpPy) | [Source Code](https://github.com/everitosan/HttpPy)

Python based HttpPy for more comfortable requests. Great replacement of wget command (Windows users, most welcome 😇)


## [Episode 324](https://talkpython.fm/episodes/show/324/gatorade-powered-python-apis)

- Title: Gatorade-powered Python APIs
- Published Fri, Jul 9, 2021, recorded Thu, Jul 8, 2021.
- Guest: Rod Senra [@rodsenra](https://twitter.com/rodsenra)

1. **rich** - *Render rich text, tables, progress bars, syntax highlighting, markdown and more to the terminal.* [PyPi](https://pypi.org/project/rich) | [Homepage](https://rich.readthedocs.io/en/latest/) | [Source Code](https://github.com/willmcgugan/rich)

<img src="https://user-images.githubusercontent.com/12855744/139004864-c8119f75-796f-45a1-8341-15db6e86caed.png" width="50%">

Rich is a Python library for rich text and beautiful formatting in the terminal. The Rich API makes it easy to add color and style to terminal output. Rich can also render pretty tables, progress bars, markdown, syntax highlighted source code, tracebacks, and more** - * out of the box. Hey, don't forget to try: ```from rich import print```, most welcome 😎

<img src="https://user-images.githubusercontent.com/12855744/139005130-c2b41766-f685-4aed-a763-6a12d3df05b2.png" width="70%">


## [Episode 323](https://talkpython.fm/episodes/show/323/best-practices-for-docker-in-production)

- Title: Best practices for Docker in production
- Published Sat, Jul 3, 2021, recorded Mon, Jun 14, 2021.
- Guest: Itamar Turner-Trauring [@itamarst](https://twitter.com/itamarst)

1. **PyO3** - *Using Python from Rust.* PyPi - n/a | [Homepage](https://pyo3.rs) | [Source Code](https://github.com/PyO3/pyo3)

<img src="https://user-images.githubusercontent.com/12855744/139005910-8a2325eb-88a4-4e7b-92bb-37d5e2319be2.png" width="35%">

Rust bindings for Python, including tools for creating native Python extension modules. Running and interacting with Python code from a Rust binary is also supported.


## [Episode 322](https://talkpython.fm/episodes/show/322/a-path-into-data-science)

- Title: A path into data science
- Published Fri, Jun 25, 2021, recorded Thu, Jun 10, 2021.
- Guest: Sanyam Bhutani [@bhutanisanyam1](https://twitter.com/bhutanisanyam1)

1. **fastai** - *Making neural nets uncool again.* [PyPi](https://pypi.org/project/fastai) | [Homepage](https://www.fast.ai/) | [Source Code](https://github.com/fastai/fastai/)

<img src="https://user-images.githubusercontent.com/12855744/139035317-9e901c29-a2e8-4a99-a813-b3f990080f71.png" width="50%">

Simplifies training fast and accurate neural nets using modern best practices.


## [Episode 321](https://talkpython.fm/episodes/show/321/htmx-clean-dynamic-html-pages)

- Title: HTMX - Clean, Dynamic HTML Pages
- Published Sat, Jun 19, 2021, recorded Tue, May 25, 2021.
- Guest: Carson Gross [@htmx_org](https://twitter.com/htmx_org)

1. **Alpine.js* PyPi | [Homepage](https://alpinejs.dev/) | [Source Code](https://github.com/alpinejs/alpine)

<img src="https://user-images.githubusercontent.com/12855744/139036749-7e03c867-3e7b-452d-a2c0-a308759278c7.png" width="50%">

This is not a PyPi package, but it is a amazing: a new, lightweight, JavaScript framework.


## [Episode 320](https://talkpython.fm/episodes/show/320/python-in-the-electrical-energy-sector)

- Title: Python in the Electrical Energy Sector
- Published Sat, Jun 12, 2021, recorded Sun, Jun 6, 2021.
- Guest: Jack Simpson's [Site](https://jacksimpson.co/)

1. **numba** - *Accelerate Python Functions by compiling Python code using LLVM.* [PyPi](https://pypi.org/project/numba/) | [Homepage](https://numba.pydata.org/) | [Source Code](https://github.com/numba/numba)

<img src="https://user-images.githubusercontent.com/12855744/139037395-c5ebcf43-9b4e-4234-ad71-2fb2fd1a80ab.png" width="50%">

Numba translates Python functions to optimized machine code at runtime using the industry-standard LLVM compiler library. Numba-compiled numerical algorithms in Python can approach the speeds of C or FORTRAN. You don't need to replace the Python interpreter, run a separate compilation step, or even have a C/C++ compiler installed. Just apply one of the Numba decorators to your Python function, and Numba does the rest.


## [Episode 319](https://talkpython.fm/episodes/show/319/typosquatting-and-supply-chains-vulnerabilities)

- Title: Typosquatting and Supply Chains Vulnerabilities
- Published Sun, Jun 6, 2021, recorded Wed, May 26, 2021.
- Guests: Bentz Tozer's [email](btozer@iqt.org) | John Speed Meyers's [email](jmeyers@iqt.org)

1. **NetworkML** - *Device Functional Role ID via Machine Learning and Network Traffic Analysis.* [PyPi](https://pypi.org/project/networkml) | [Homepage](https://github.com/IQTLabs/NetworkML) | [Source Code](https://github.com/IQTLabs/NetworkML)

NetworkML is the machine learning portion of our Poseidon project. The model in networkML classifies each device into a functional role via machine learning models trained on features derived from network traffic. "Functional role" refers to the authorized administrative purpose of the device on the network and includes roles such as printer, mail server, and others typically found in an IT environment. Our internal analysis suggests networkML can achieve accuracy, precision, recall, and F1 scores in the high 90's when trained on devices from your own network. Whether this performance can transfer from IT environment to IT environment is an active area of our research. Dear network administrator 🏃🏃🏃🏃🏃, NetworkML predicts the functional role of network-connected device via network traffic analysis and machine learning.


## [Episode 318](https://talkpython.fm/episodes/show/318/measuring-your-ml-impact-with-codecarbon)

- Title: Measuring your ML impact with CodeCarbon
- Published Fri, May 28, 2021, recorded Wed, May 19, 2021.
- Guests: Victor Schmidt [@vict0rsch](https://twitter.com/vict0rsch) | Jonathan Wilson's [Webpage](https://www.haverford.edu/) | Boris Feld [@Lothiraldan](https://twitter.com/Lothiraldan)

1. **rich** - *Render rich text, tables, progress bars, syntax highlighting, markdown and more to the terminal.* [PyPi](https://pypi.org/project/rich) | [Homepage](https://rich.readthedocs.io/en/latest/) | [Source Code](https://github.com/willmcgugan/rich)

<img src="https://user-images.githubusercontent.com/12855744/139004864-c8119f75-796f-45a1-8341-15db6e86caed.png" width="50%">

Rich is a Python library for rich text and beautiful formatting in the terminal. The Rich API makes it easy to add color and style to terminal output. Rich can also render pretty tables, progress bars, markdown, syntax highlighted source code, tracebacks, and more — out of the box. Hey, don't forget to try: ```from rich import print```, most welcome 😎

<img src="https://user-images.githubusercontent.com/12855744/139005130-c2b41766-f685-4aed-a763-6a12d3df05b2.png" width="70%">

2. **FastAPI** - *A-W-E-S-O-M-E web framework for building APIs.* [PyPi](https://pypi.org/project/fastapi) | [Homepage](https://fastapi.tiangolo.com/) | [Source Code](https://github.com/tiangolo/fastapi)

<img src="https://user-images.githubusercontent.com/12855744/139193341-51a8e2d9-0b8d-4b36-b20e-df1ac103d0a5.png" width="50%">

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. In addition to the API type check feature, I think that the automatic interactive API documentation provided by Swagger UI is 🤯


## [Episode 317](https://talkpython.fm/episodes/show/317/python-at-the-us-federal-election-commission)

- Title: Python at the US Federal Election Commission
- Published Fri, May 21, 2021, recorded Wed, May 19, 2021.
- Guest: Laura Beaufort [@laurabeaufort](https://twitter.com/@laurabeaufort)
 
1. **Flask-SQLAlchemy** - *Adds SQLAlchemy support to your Flask application.* [PyPi](https://pypi.org/project/flask_sqlalchemy) | [Homepage](https://flask-sqlalchemy.palletsprojects.com) | [Source Code](https://github.com/pallets/flask-sqlalchemy)

<img src="https://user-images.githubusercontent.com/12855744/139461078-a30c15ae-1d06-49a3-8cb0-f715c11a5d17.png" width="50%">

Flask-SQLAlchemy is an extension for Flask that adds support for SQLAlchemy to your application. It aims to simplify using SQLAlchemy with Flask by providing useful defaults and extra helpers that make it easier to accomplish common tasks.


## [Episode 316](https://talkpython.fm/episodes/show/316/flask-2.0)

- Title: Flask 2.0
- Published Fri, May 14, 2021, recorded Mon, May 10, 2021.
- Guests: David Lord [@davidism](https://twitter.com/davidism) | Philip Jones [@pdgjones](https://twitter.com/pdgjones) 

1. **Pydantic** - *Data validation and settings management.* [PyPi](https://pypi.org/project/pydantic/) | [Homepage](https://pydantic-docs.helpmanual.io/) | [Source Code](https://github.com/samuelcolvin/pydantic/)

Data validation and settings management using python type annotations. `pydantic` enforces type hints at runtime, and provides user friendly errors when data is invalid.

2. **AutoInvent** - *Libraries for generating GraphQL API and UI from data.* [PyPi](https://pypi.org/project/magql/) | [Homepage](https://autoinvent.dev) | [Source Code](https://github.com/autoinvent/)

Magql is a GraphQL framework for Python. It generates a full-featured, customizable GraphQL API for your data. It's pronounced "magical", and it is!

3. **trio** - *A friendly Python library for async concurrency and I/O.* [PyPi](https://pypi.org/project/trio) | [Homepage](https://trio.readthedocs.io/en/stable/) | [Source Code](https://github.com/python-trio/trio)

<img src="https://warehouse-camo.ingress.cmh1.psfhosted.org/f63e71fb87f195504ac2e118f423678fdd382d94/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f707974686f6e2d7472696f2f7472696f2f396230626563363436613331653064306636376238623665636336393339373236666166336531372f6c6f676f2f6c6f676f2d776974682d6261636b67726f756e642e737667" width="35%">

The Trio project’s goal is to produce a production-quality, permissively licensed, async/await-native I/O library for Python. Like all async libraries, its main purpose is to help you write programs that do multiple things at the same time with parallelized I/O.


## [Episode 315](https://talkpython.fm/episodes/show/315/awesome-fastapi-extensions-and-add-ons)

- Title: Awesome FastAPI extensions and add ons
- Published Fri, May 7, 2021, recorded Thu, Apr 22, 2021.
- Guest: Michael Herman [@mikeherman](https://twitter.com/mikeherman)

1. **flake8-docstrings** [PyPi](https://pypi.org/project/flake8-docstrings/) | [Homepage](https://github.com/pycqa/flake8-docstrings) | [Source Code](https://github.com/pycqa/flake8-docstrings)

<img src="https://user-images.githubusercontent.com/12855744/139466227-2d1f4e07-2587-46ed-8ae0-2f40a2096df3.png" width="50%">

A simple module that adds an extension for the fantastic pydocstyle tool to flake8.

2. **hotwire-django** [PyPi](https://pypi.org/project/hotwire-django/) | [Homepage](https://github.com/hotwire-django/hotwire-django) | [Source Code](https://github.com/hotwire-django/hotwire-django)

This repository aims to help you integrate Hotwire with Django🚀. Inspiration might be taken from @hotwired/hotwire-rails.


## [Episode 314](https://talkpython.fm/episodes/show/314/ask-us-about-modern-python-projects-and-tools)

- Title: Ask us about modern Python projects and tools
- Published Fri, Apr 30, 2021, recorded Mon, Apr 19, 2021.
- Guest: Sebastian Witowski [@SebaWitowski](https://twitter.com/SebaWitowski)

1. **Awesome Python** - *Life is short, you need Python.* PyPi | [Homepage](https://awesome-python.com/) | [Source Code](https://github.com/vinta/awesome-python/)

![image](https://user-images.githubusercontent.com/12855744/139469805-289c2835-4d9a-4f54-a5e5-8022371365c1.png)

A curated list of awesome Python frameworks, libraries, software and resources. Inspired by awesome-php.



## [Episode 313](https://talkpython.fm/episodes/show/313/automate-your-data-exchange-with-pydantic)

- Title: Automate your data exchange with PyDantic
- Published Thu, Apr 22, 2021, recorded Wed, Apr 14, 2021.
- Guest: Samuel Colvin [@samuel_colvin](https://twitter.com/samuel_colvin)

1. **Starlette** - *The little ASGI library that shines.* [PyPi](https://pypi.org/project/starlette) | [Homepage](https://github.com/encode/starlette) | [Source Code](https://github.com/encode/starlette)

<img src="https://user-images.githubusercontent.com/12855744/139470371-154d880a-04ab-47e0-be6e-9633011b6e30.png" width="50%">

Starlette is a lightweight ASGI framework/toolkit, which is ideal for building high performance async services.



## [Episode 312](https://talkpython.fm/episodes/show/312/python-apps-that-scale-to-billions-of-users)

- Title: Python Apps that Scale to Billions of Users
- Published Sun, Apr 18, 2021, recorded Thu, Apr 8, 2021.
- Guest: Julien Danjou [@juldanjou](https://twitter.com/juldanjou)

1. **tenacity** - *Retry code until it succeeds* [PyPi](https://pypi.org/project/tenacity/) | [Homepage](https://tenacity.readthedocs.io/en/latest/) | [Source Code](https://github.com/jd/tenacity)

Tenacity is an Apache 2.0 licensed general-purpose retrying library, written in Python, to simplify the task of adding retry behavior to just about anything. It originates from a fork of retrying which is sadly no longer maintained. Tenacity isn't api compatible with retrying but adds significant new functionality and fixes a number of longstanding bugs.



## [Episode 311](https://talkpython.fm/episodes/show/311/get-inside-the-.git-folder)

- Title: Get inside the .git folder
- Published Thu, Apr 8, 2021, recorded Thu, Apr 1, 2021.
- Guest: Rob Richardson [@rob_rich](https://twitter.com/rob_rich)


1. **git-hooks-js** - *Utility for managing and running project git hooks for nodejs projects.* ~~PyPi~~ [npm](https://www.npmjs.com/package/git-hooks) | [Homepage](https://www.npmjs.com/package/git-hooks) | [Source Code](https://github.com/tarmolov/git-hooks-js)

git-hooks is an utility for managing and running project git hooks for nodejs projects. It has zero dependecies and easy to use. Just install git-hooks and it will run your hooks when a hook is called by git.



## [Episode 310](https://talkpython.fm/episodes/show/310/ama-ask-me-anything-with-michael)

- Title: AMA (Ask Me Anything) with Michael
- Published Fri, Apr 2, 2021, recorded Wed, Mar 31, 2021.
- Guests: Kim van Wyk [@kim_vanwyk](https://twitter.com/kim_vanwyk) | Patrik Hlobil [@hlobilpatrik](https://twitter.com/hlobilpatrik)

1. **pySerial** - *Python Serial Port Extension.* [PyPi](https://pypi.org/project/pyserial) | [Homepage](https://github.com/pyserial/pyserial) | [Source Code](https://github.com/pyserial/pyserial)

<img src="https://user-images.githubusercontent.com/12855744/139531073-3353bd6c-597f-4d87-95b1-b115cc1a61b8.png" width="50%">

This module encapsulates the access for the serial port. It provides backends for Python running on Windows, OSX, Linux, BSD (possibly any POSIX compliant system) and IronPython. The module named "serial" automatically selects the appropriate backend.

2. **Click** - *Composable command line interface toolkit.* [PyPi](https://pypi.org/project/Click) | [Homepage](https://palletsprojects.com/p/click/) | [Source Code](https://github.com/pallets/click/)

<img src="https://user-images.githubusercontent.com/12855744/139531131-9e235afa-0b12-469e-85b7-8dbe4cc80c11.png" width="50%">

Click is a Python package for creating beautiful command line interfaces in a composable way with as little code as necessary. It’s the “Command Line Interface Creation Kit”. It’s highly configurable but comes with sensible defaults out of the box. It aims to make the process of writing command line tools quick and fun while also preventing any frustration caused by the inability to implement an intended CLI API.


## [Episode 309](https://talkpython.fm/episodes/show/309/what-ml-can-teach-us-about-life-7-lessons)

- Title: What ML Can Teach Us About Life: 7 Lessons
- Published Fri, Mar 26, 2021, recorded Fri, Mar 19, 2021.
- Guest: Eugene Yan [@eugeneyan](https://twitter.com/eugeneyan)

1. **Pytest** - *Simple powerful testing with Python.* [PyPi](https://pypi.org/project/pytest) | [Homepage](https://docs.pytest.org/) | [Source Code](https://github.com/pytest-dev/pytest)

<img src="https://user-images.githubusercontent.com/12855744/139531324-1e9f3ae6-934c-4bf9-bd10-22a16fb50cb4.png" width="50%">

The pytest framework makes it easy to write small tests, yet scales to support complex functional testing for applications and libraries. Can you belive that [Brian Okken](https://twitter.com/brianokken) has a [book](https://pragprog.com/titles/bopytest2/python-testing-with-pytest-second-edition/) about it? lol


## [Episode 308](https://talkpython.fm/episodes/show/308/docker-for-python-developers-2021-edition)

- Title: Docker for Python Developers (2021 Edition)
- Published Sat, Mar 20, 2021, recorded Tue, Mar 9, 2021.
- Guest: Peter McKee [@pmckee](https://twitter.com/pmckee)

1. **testcontainers-python** - *Test almost anything that can run in a Docker container.* [PyPi](https://pypi.org/project/testcontainers/) | [Homepage](https://github.com/testcontainers/testcontainers-python) | [Source Code](https://github.com/testcontainers/testcontainers-python)

<img src="https://user-images.githubusercontent.com/12855744/139531692-5cbfae15-b014-48f3-b3ec-b0e3b3a3fdc1.png" width="50%">

Testcontainers-python provides capabilities to spin up docker containers (such as a database, Selenium web browser, or any other container) for testing.


## [Episode 307](https://talkpython.fm/episodes/show/307/python-from-1994-to-2021-my-how-youve-grown)

- Title: Python from 1994 to 2021, my how you've grown!
- Published Thu, Mar 11, 2021, recorded Thu, Mar 4, 2021.
- Guests: Paul Everitt [@paulweveritt](https://twitter.com/paulweveritt) | Barry Warsaw [@pumpichank](https://twitter.com/pumpichank)

There was no time for notable package, but it was an great episode! 


## [Episode 306](https://talkpython.fm/episodes/show/306/scaling-python-and-jupyter-with-zeromq)

- Title: Scaling Python and Jupyter with ZeroMQ
- Published Fri, Mar 5, 2021, recorded Thu, Feb 11, 2021.
- Guest: Min Ragan-Kelley [@minrk](https://twitter.com/minrk)

1. **cibuildwheel** - *Build Python wheels on CI with minimal configuration.* [PyPi](https://pypi.org/project/cibuildwheel) | [Homepage](https://cibuildwheel.readthedocs.io/en/stable/) | [Source Code](https://github.com/pypa/cibuildwheel)

<img src="https://user-images.githubusercontent.com/12855744/139532144-a80f1b2b-d214-48b2-8c08-721fcc5b6ef8.png" width="50%">

Python wheels are great. Building them across Mac, Linux, Windows, on multiple versions of Python, is not. ```cibuildwheel``` runs on your CI server - currently it supports GitHub Actions, Azure Pipelines, Travis CI, AppVeyor, CircleCI, and GitLab CI - and it builds and tests your wheels across all of your platforms.


## [Episode 305](https://talkpython.fm/episodes/show/305/python-community-at-python-discord)

- Title: Python community at Python Discord
- Published Mon, Mar 1, 2021, recorded Thu, Feb 11, 2021.
- Guest: Leon Sandøy [@lemonsaurus_rex](https://twitter.com/lemonsaurus_rex)

1. **async-rediscache** - *An easy to use asynchronous Redis cache.* [PyPi](https://pypi.org/project/async-rediscache/) | [Homepage](https://github.com/SebastiaanZ/async-rediscache) | [Source Code](https://github.com/SebastiaanZ/async-rediscache)

<img src="https://user-images.githubusercontent.com/12855744/139570548-1d70a874-3d83-4eb2-9d92-177f1ef3dea9.png" width="50%">

This package offers several data types to ease working with a Redis cache in an asynchronous workflow. The package is currently in development and it's not recommended to start using it in production at this point.



## Your support is always welcome

The $100, 60-day free trial provides free credit up to $100 that must be used within 60 days  [![DigitalOcean Referral Badge](https://web-platforms.sfo2.cdn.digitaloceanspaces.com/WWW/Badge%201.svg)](https://www.digitalocean.com/?refcode=440844193481&utm_campaign=Referral_Invite&utm_medium=Referral_Program&utm_source=badge)

<a href="https://www.buymeacoffee.com/AntonioAndrade ">
<img src="https://user-images.githubusercontent.com/12855744/165140444-8f024292-f752-477f-b62d-fa1a671c4cda.png" width="50%">
</a>


## [Episode 304](https://talkpython.fm/episodes/show/304/asyncio-all-the-things-with-omnilib)

- Title: asyncio all the things with Omnilib
- Published Sun, Feb 21, 2021, recorded Tue, Feb 16, 2021.
- Guest: John Reese [@n7cmdr](https://twitter.com/n7cmdr)

1. **seinfeld** - *Query a Seinfeld quote database* [PyPi](https://pypi.org/project/seinfeld/) | [Homepage](https://github.com/jreese/libseinfeld) | [Source Code](https://github.com/jreese/libseinfeld)

<img src="https://user-images.githubusercontent.com/12855744/139571052-5c0dde9a-39ca-421c-83d9-981c51a0ff62.png" width="50%">

Python library for querying Seinfeld quotes. Oh yeah, Seinfeld.


## [Episode 303](https://talkpython.fm/episodes/show/303/python-for-astronomy-with-dr.-becky)

- Title: Python for Astronomy with Dr. Becky
- Published Fri, Feb 12, 2021, recorded Thu, Feb 4, 2021.
- Guest: Dr. Becky Smethurst [@drbecky_](https://twitter.com/drbecky_)


1. **notebook** - *A web-based notebook environment for interactive computing.* [PyPi](https://pypi.org/project/notebook/) | [Homepage](https://jupyter-notebook.readthedocs.io/en/stable/) | [Source Code](https://github.com/jupyter/notebook/)

<img src="https://user-images.githubusercontent.com/12855744/139571508-898ce721-bc6f-474f-86c6-06484c0b7592.png" width="50%">

The Jupyter Notebook is a web application that allows you to create and share documents that contain live code, equations, visualizations, and explanatory text. The Notebook has support for multiple programming languages, sharing, and interactive widgets.



## [Episode 302](https://talkpython.fm/episodes/show/302/the-data-engineering-landscape-in-2021)

- Title: The Data Engineering Landscape in 2021
- Published Thu, Feb 4, 2021, recorded Fri, Jan 29, 2021.
- Guest: Tobias Macey [@TobiasMacey](https://twitter.com/TobiasMacey)

1. **dagster** - *A data orchestrator for machine learning, analytics, and ETL.*  [PyPi](https://pypi.org/project/dagster) | [Homepage](https://dagster.io/) | [Source Code](https://github.com/dagster-io/dagster)

<img src="https://user-images.githubusercontent.com/12855744/139571650-3f19c5df-a025-4451-8963-52d4de7c6bd4.png" width="50%">

An orchestration platform for the development, production, and observation of data assets. Dagster lets you define jobs in terms of the data flow between reusable, logical components, then test locally and run anywhere. With a unified view of jobs and the assets they produce, Dagster can schedule and orchestrate Pandas, Spark, SQL, or anything else that Python can invoke. Dagster is designed for data platform engineers, data engineers, and full-stack data scientists. Building a data platform with Dagster makes your stakeholders more independent and your systems more robust. Developing data pipelines with Dagster makes testing easier and deploying faster.



## [Episode 301](https://talkpython.fm/episodes/show/301/deploying-and-running-django-web-apps-in-2021)

- Title: Deploying and running Django web apps in 2021
- Published Thu, Jan 28, 2021, recorded Tue, Jan 19, 2021.
- Guests: Will Vincent's [Web](https://wsvincent.com) | Carlton Gibson [@carltongibson](https://twitter.com/carltongibson)

1. **bleach** - *An easy safelist-based HTML-sanitizing tool.* [PyPi](https://pypi.org/project/bleach/) | [Homepage](https://github.com/mozilla/bleach) | [Source Code](https://github.com/mozilla/bleach)

<img src="https://user-images.githubusercontent.com/12855744/139571798-fdfe0fce-b583-4351-bb84-383c4e8ac6d5.png" width="50%">

`Bleac`h is an allowed-list-based HTML sanitizing library that escapes or strips markup and attributes. Bleach can also linkify text safely, applying filters that Django's urlize filter cannot, and optionally setting rel attributes, even on links already in the text. Bleach is intended for sanitizing text from untrusted sources. If you find yourself jumping through hoops to allow your site administrators to do lots of things, you're probably outside the use cases. Either trust those users, or don't.


## [Episode 300](https://talkpython.fm/episodes/show/300/building-a-data-science-startup-panel)

- Title: Building a data science startup (panel)
- Published Fri, Jan 22, 2021, recorded Thu, Jan 7, 2021.
- Guest: Ines Montani [@_inesmontani](https://twitter.com/_inesmontani) | Matthew Rocklin  [@mrocklin](https://twitter.com/mrocklin) | Jonathon Morgan [@jonathonmorgan](https://twitter.com/jonathonmorgan) | William Stein [@wstein389](https://twitter.com/wstein389)

There was no time for notable package, but it was an great episode! 


## [Episode 299](https://talkpython.fm/episodes/show/299/personal-search-engine-with-datasette-and-dogsheep)

- Title: Personal search engine with datasette and dogsheep
- Published Sun, Jan 17, 2021, recorded Wed, Nov 18, 2020.
- Guest: Simon Willison [@simonw](https://twitter.com/simonw)

1. **flynt** - *String formatting converter.* [PyPi](https://pypi.org/project/flynt/) | [Homepage](https://github.com/ikamensh/flynt) | [Source Code](https://github.com/ikamensh/flynt)

`flynt` is a command line tool to automatically convert a project's Python code from old "%-formatted" and .format(...) strings into Python 3.6+'s "f-strings".

## [Episode 298](https://talkpython.fm/episodes/show/298/building-ml-teams-and-finding-ml-jobs)

- Title: Building ML teams and finding ML jobs
- Published Mon, Jan 11, 2021, recorded Wed, Nov 18, 2020.
- Guest: Chip Huyen [@chipro](https://twitter.com/chipro)

1. **papermill** - *Parameterizing, executing, and analyzing Jupyter Notebooks.* [PyPi](https://pypi.org/project/papermill/) | [Homepage](https://github.com/nteract/papermill) | [Source Code](https://github.com/nteract/papermill)

<img src="https://user-images.githubusercontent.com/12855744/166134850-5306eaac-cbba-4179-9c6b-d5140a66241e.png" width="50%">

`papermill` is a tool for parameterizing, executing, and analyzing Jupyter Notebooks.

# 2020
# 2019
# 2018
# 2017
# 2016
# 2015
