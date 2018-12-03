---
layout: base
---

# Audience

HPC Carpentry's materials were developed to meet the needs of researchers who are 
outgrowing their laptops and desktops as the "home" for their computational work.  
Many of these researchers have limited familiarity with the command line and 
have never used a large-scale, shared system (maybe have never logged into a remote 
server!) and aren't familiar with what a scheduler does, much less how to use one.  

See below for specific examples of what this might look like in different domains.  

## Learner Profiles

Here we've borrowed from the concept of "user profiles" or 
"[user modeling][user-modeling]" in the world of user interface design to 
create "learner profiles" of a potential learner at an 
HPC Carpentry workshop.  These profiles describe some of a learner's background 
experience, skills, motivation, and goals.  

> ## Environmental Biology
> 
> Y. is an environmental biologist that uses DNA signatures obtained from
> soils to study species diversity in the environment. 
> She need to compare DNA sequences to large databases. So far, she has
> been able to use web-based tools for her limited datasets.
> 
> Recently, Y has started working with much larger datasets, and
> discovered that the online tool he uses has a limit of 50 entries on the
> online server. 
> He has heard it should be possible to run the same tool through the
> command line, and managed to install it on his local Laptop. 
> Now, however, it takes several days before each of the analyses are
> finished.
> 
> The workshop will teach Y to move his data to and from the university's
> computer cluster, and submit jobs using pre-installed software on the
> cluster. 
> Afterwards, Y will be able to analyze her own data and pre-installed
> command-line based versions of the tool
> to spread the analysis over several dozen cores so it finishes in a few
> hours.

> ## Physics (or many other domains!)
> 
> A new PhD student is given a task to select parameters for their
> simulation.  They need to run a set of calculations on several thousand 
> combinations of parameters.  One calculation takes several minutes. 
> They set up the problem on their laptop but quickly realise 
> that it would take more than one month to complete the task. 
> They are told to use local HPC but they are not sure how this would help
> them.

> ## General Learner Characteristics
> 
> * Knowlededgeable in their (non-computational!) domain
> * Priority is to get their work done, not necessarily to learn about computers
> * Doesn't know what large scale computing (Cloud? HPC? Grid?) is or why it can help them; may think that programs will automatically run faster on a cluster
> * Haven't used a shared system before
> * Are not familiar with many of the terms (threads, cores) or concepts (scheduling) that are key to running on a shared batch system
> * May have some command line or programming experience, but not necessarily; may have only used GUIs in the past

This type of audience needs an introduction to large-scale computational resources that 
helps them see how these resources could help them and transform their research, 
and give them enough conceptual knowledge and practical skills to go from their local 
computer to basic usage of a large-scale system.  

# Why HPC Carpentry?  

While there are many materials available that address high-performance computing environments, 
including, but not limited to supercomputers, campus clusters, distributed high throughput 
systems and cloud computing, there is a relative lack of *introductory* materials for 
the novice audience described above.  Most materials currently available either 
assume a certain level of prerequisite knowledge,
or are in the wrong format for introductory workshops 
(either lecture-based or have a very long teaching time).

Until recently, the best option for teaching basic workshops on remote, large-scale  
compute resources was to teach one of the popular [Software Carpentry][swc] workshops, 
with a brief HPC component tacked on or crammed into various sections. 
This was not a good solution in most cases - 
Software Carpentry's materials are already more or less "full" 
(something added comes at the expense of something else),
and the languages/topics of the workshops 
was not particularly well matched for problems commonly encountered in HPC
(for instance, hardcore number crunching or execution of large numbers of externally 
written programs and tools).

See [About HPC Carpentry](about) for information about HPC Carpentry in general
and [Running a workshop](workshops) for details about how to run your own HPC 
Carpentry workshop.  

Instructors simply looking to teach basic programming skills in R or Python 
are highly encouraged to check out the materials offered by 
[Software Carpentry][swc].
Software Carpentry's lessons are more generally applicable 
introductory programming materials that do not have an HPC component.

[swc]: https://software-carpentry.org/
[user-modeling]: https://en.wikipedia.org/wiki/User_modeling
