# The Future of Python on HPC Systems

## Session leader information

**Name**: Andy Terrel  
**Email**: andy@numfocus.org  
**Company/Institution**: NumFOCUS  
**Country**: US  
**Biography** (up to 150 words): Andy is a leader in the Python open-source software community. He's most notably a co-creator of the Dask distributed computing framework, the Conda package manager, the SymPy symbolic computing library, and NumFOCUS foundation. His research focused on domain-specific languages to generate high-performance code for physics simulations with the PETSc and FEniCS projects.


**Name**: Barry Warsaw  
**Email**: barry@python.org  
**Company/Institution**: Python Software Foundation  
**Country**: US  
**Biography** (up to 150 words): Barry is a long-time Core CPython Developer and a current member of the Python Steering Council. With decades of experience contributing to the language, Barry has played a central role in shaping Python’s evolution, from its early design decisions to its modern governance structure. He brings deep expertise in language standards, packaging, and interoperability, and is a strong advocate for making Python more robust and accessible across diverse computing environments. Barry’s insights are particularly valuable to the HPC community as Python continues to adopt new paradigms like JIT compilation, async primitives, and modular packaging standards. 


**Name**: Michael Droettboom  
**Email**: mdboom@gmail.com   
**Company/Institution**: Microsoft  
**Country**: US  
**Biography** (up to 150 words): Michael Droettboom is a distinguished CPython core developer who has led the Faster CPython team, driving the integration of a JIT compiler into the main interpreter. Under his leadership, Python 3.14 achieved 20–40% speed improvements over 3.10, and experimental JIT support was merged alongside a specializing adaptive interpreter . At Microsoft, he managed performance engineering—developing benchmarking tools like pyperf and bench_runner. A key contributor to the scientific Python ecosystem, Michael was the former lead maintainer of Matplotlib, a primary contributor to Astropy, and the creator of Pyodide—bringing the full Python stack to WebAssembly in the browser. His work combines deep expertise in performance optimization and scientific computing, making him a vital voice in shaping Python’s future for HPC and research communities.

**Name**: Carol Willing  
**Email**: willingc@gmail.com  
**Company/Institution**: Python Software Foundation  
**Country**: US   
**Biography** (up to 150 words): Carol Willing is a Core CPython Developer and three-time member of the Python Steering Council, recognized as a Python Software Foundation Fellow. She’s also a key contributor to the Project Jupyter ecosystem—helping to develop Jupyter Notebook, JupyterHub, and MyBinder—and earned the 2017 ACM Software System Award for her work on Jupyter . Carol advocates for open science and inclusive software governance, advising organizations like Quansight Labs and the Chan Zuckerberg Initiative. She co-authored Teaching and Learning with Jupyter, serves as co-editor of the Journal of Open Source Education, and mentors through PyLadies San Diego and the San Diego Python User Group. Her unique blend of technical leadership and community-building makes her an invaluable voice for advancing Python in scientific and HPC domains.

**Name**: Bryce Lelbach  
**Email**: blelbach@nvidia.com  
**Company/Institution**: NVIDIA  
**Country**: US  
**Biography** (up to 150 words):  Bryce Adelstein Lelbach is a Principal Architect at NVIDIA, where he leads efforts in programming language design for HPC. He spearheads the development of cuTile, an innovative tile-based programming model for CUDA Python. Bryce has over a decade of experience building compilers, libraries, and runtime systems; he helped initiate the HPX parallel runtime and previously led the CUDA C++ Core Libraries. He also chairs key U.S. and ISO C++ standards committees, influencing areas like concurrency, parallel algorithms, and multidimensional arrays. Bryce’s deep expertise in language design and HPC compiler technology positions him as a transformative force in shaping next-generation accelerator programming models.


**Name**: Davin Potts  
**Email**: davin@appliomics.com  
**Company/Institution**: HPE / Cray  
**Country**: US  
**Biography** (up to 150 words): Davin Potts is a Core CPython Developer best known for his work maintaining and improving Python’s multiprocessing module. He led the development of the shared_memory feature introduced in Python 3.8, which allows processes to efficiently share data without copying. Davin has focused on making parallel computing in Python more robust and accessible for real-world use. He also brings deep expertise from his role as on the Dragon HPC system at HPE/Cray, where he works on next-generation supercomputing platforms. His combined experience in Python and HPC makes him a key contributor to advancing Python’s performance in high-end computing environments.

## Selection of a topic area that best fits your BoF (see below);

Standards  
Practitioners in HPC  
Community Meetings  
Democratization of HPC  
State of the Practice

## Abstract 
(100-word maximum)

Python is the most widely used programming language today—but on HPC systems, it’s often more pain than power. From slow module loading on shared filesystems to packaging headaches and incompatible distributions, these hurdles block new users and frustrate seasoned developers alike. Meanwhile, major changes to Python’s core — new Array APIs, packaging reforms, JIT compilation, and threading primitives —- are happening without HPC at the table. This BoF brings together language leaders and HPC practitioners to change that. Join us to shape Python’s future, learn what’s coming, connect with peers, and help launch a new HPC working group to influence Python from the inside out.


## Long description 
(500-word maximum) clearly stating goal(s), topic, relevance to the expected HPC audience, and the expected outcome; and

Python is the world’s most widely used programming language, powering everything from machine learning and data analysis to web development and automation. However, using Python effectively on high-performance computing (HPC) systems presents unique and persistent challenges. These issues often prevent new users from realizing the full power of supercomputers, and they frustrate seasoned practitioners who rely on Python for scientific computing.

The Python HPC ecosystem is highly fragmented. Language implementers, library developers, and HPC users often operate in silos with little coordination. As a result, critical challenges faced by HPC Python users go unaddressed at the language and standards level, and efforts to improve performance and usability on HPC platforms remain scattered and under-resourced.

This Birds of a Feather (BoF) session aims to build stronger connections between the global scientific Python community, the Python language maintainers, and the HPC community. Our goal is to create an ongoing dialogue that ensures the needs of HPC users are represented as Python evolves.

Common runtime issues faced by HPC users include:
- Python’s module system, when run on shared filesystems, introduces significant latency in program startup.
- Python’s default packaging tools struggle to support specialized libraries such as optimized MPI stacks or system-tuned numerical libraries.
- Parallelism tools in Python—ranging from threading to multiprocessing to MPI bindings—are often incompatible or difficult to integrate.
- Despite the size and impact of the HPC Python user base, it remains underrepresented in broader Python discussions, including at core language and packaging summits.

At the same time, the Python language itself is evolving rapidly. A number of active Python Enhancement Proposals (PEPs) will have far-reaching effects on the HPC ecosystem, but currently, there is minimal overlap between HPC stakeholders and the Python Steering Council or other decision-making bodies. Relevant ongoing work includes:

- Standardizing array APIs and memory models to improve interoperability between libraries and accelerators.
- Evolving packaging standards to better accommodate system-level and cross-platform deployments.
- Developing just-in-time (JIT) compilation frameworks at the bytecode level, with implications for performance-critical workloads.
- Introducing new asynchronous and parallel programming primitives at the language level.

These changes present both opportunities and risks for the HPC community. Without input from HPC practitioners, new language features may fall short of supercomputing needs or introduce new bottlenecks. With the right engagement, however, these changes could significantly improve Python’s performance, portability, and productivity in HPC environments.

To that end, we are inviting leaders from the core Python development team to participate in this BoF and hear directly from HPC practitioners. Our goals are to:

- Equip attendees with an understanding of upcoming Python language standards and how they may impact scientific and HPC workloads.
- Connect practitioners with one another to share solutions and align on priorities.
- Create shared documentation and communication channels to support sustained collaboration.
- Lay the groundwork for an official Python HPC Working Group that can represent HPC interests to the Python Software Foundation and language governance bodies.

Join us to help shape the future of Python on supercomputers—and ensure your voice is heard.

## Session format information, 
including a description (150-word maximum) of how you plan to organize the BoF session.

The BoF session will begin with a brief 5-minute introduction to set the context for attendees. During this segment, we will briefly outline key challenges in using Python on HPC systems and introduce the evolving language standards that are most relevant. To ground this discussion, each major standard will be presented by a speaker using a single slide, offering concise overviews of topics such as array APIs, packaging, JIT, and async primitives. Confirmed speakers include Barry Warsaw, Michael Droetboom, and Carol Willing.

The second part of the session will be a facilitated, interactive discussion. Attendees will have the opportunity to share how these changes impact their workflows, raise challenges, and propose ideas for collaboration and solutions.

Remote participants are welcome and can engage through real-time notes on HackMD, Q&A on Slido, and live chat on the pyHPC Discord server. These platforms will ensure everyone has a voice in the conversation.

## Plan

Facilitate a discussion 
Common problems 
Translation errors between speakers

