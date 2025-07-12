# The Future of Python on HPC Systems

## Session leader information

**Name**: Andy Terrel  
**Email**: andy@numfocus.org  
**Company/Institution**: NumFOCUS  
**Country**: US  
**Biography** (up to 150 words): Andy Terrel leads NVIDIA CUDA Python from the product management team. His research focused on domain-specific languages to generate high-performance code for physics simulations with the PETSc and FEniCS projects. Andy is a leader in the Python open-source software community. He's most notably a co-creator of the Dask distributed computing framework, the Conda package manager, the SymPy symbolic computing library, and NumFOCUS foundation.


**Name**: Barry Warsaw  
**Email**: barry@python.org  
**Company/Institution**: Python Software Foundation  
**Country**: US  
**Biography** (up to 150 words): 


**Name**: Michael Droettboom  
**Email**: mdboom@gmail.com   
**Company/Institution**: Microsoft  
**Country**: US  
**Biography** (up to 150 words): 

**Name**: Carol Willing  
**Email**: willingc@gmail.com  
**Company/Institution**: Python Software Foundation  
**Country**: US   
**Biography** (up to 150 words): 

**Name**: Bryce Lelbach  
**Email**: blelbach@nvidia.com  
**Company/Institution**: NVIDIA  
**Country**: US  
**Biography** (up to 150 words):  


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

Python is the world's most popular programming language. Python on HPC systems has it's own special challenges. These challenges often prevent new comers to HPC from fully realizing the potential of supercomputers. Unfortunately this global community is fractured between language implementers, library writers, and hpc practitioners.

Our goal is to create a dialogue between the global Scientific library community, the language community and the HPC community. 

On HPC system Python runtime problems include:
- Pythons module system on shared filesystems cause large latencies in loading programs,
- Python's default packaging doesn't work well with specialized libraries on HPC systems, e.g. optimized MPIs,
- Parallel systems in Python are often incompatible with each other
- HPC Python users often claim their needs are not being heard, but are not organized at other conferences

On language front there are many standards or PEPs (Python enhancement proposals) in flight that will affect the HPC community, but largely there is zero overlap with the Python Steering Committee  These standards include:
- Array Apis and data interfaces that allow for sharing between libraries,
- Packaging standards are evolving to accommodate system libraries,
- just-in-time compilation systems are being developed at the bytecode level of the language,
- asynchronous threading primatives are being added to the language.

These recent changes in the language should have representation from the Supercomputing community, 

we are organizing leaders in the Core Python teams to take feedback from HPC practicitioners at this BOF. 
Goals for the BoF:
- Attendee will get an understanding of the the newest standards in the Python language, why they may or may not want to use them, and conections to other Python users in the field who they can network with to find common ground for finding solutions.
- Python language members can help our community be represented in updating standards (PEPs) for HPC problems
- Common documents and forums shared between both parties to continue improving Python on HPC.
- Setup a Python HPC working group that can be council to both HPC and Python Software Foundation.


## Session format information, 
including a description (150-word maximum) of how you plan to organize the BoF session.

The first part of the BOF Session will be 10 minutes setting up context for attendees. We will have a speaker with one slide setting up each new standard. Speakers identified include Barry Warsaw, Micheal Droetboom, and Carol Willing.

The second part will be a facilitated discussion giving the audience the opportunity to discuss how these standards impact their workflow.

Remote participants will be able to join via notes on HackMD, Slido and the pyHPC Discord server.

problems with the dialog:
- Standards in Python can take up to a decade to be accepted and implemented
- No single process for getting accepted, so folks have to work with the Python language community to understand the evolving process
- HPC teams don't have time feed the relationships in both the HPC and Python langauge communities



## Plan

Facilitate a discussion 
Common problems 
Translation errors between speakers

