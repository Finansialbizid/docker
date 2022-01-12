---
layout: lesson
root: .  # Is the only page that doesn't follow the pattern /:path/index.html
permalink: index.html  # Is the only page that doesn't follow the pattern /:path/index.html
---
This course aims to introduce the use of containers with the goal of using them to effect reproducible computational environments. Such environments are useful for ensuring reproducible research outputs and for simplifying the setup of complex software dependencies across different systems. The course will introduce the use of Docker and Singularity containers but the material will be of use for whatever container technology you plan to, or end up, using.

> ## After completing this session you should:
> - Have an understanding of what Docker/Singularity containers are, why they are useful and the common terminology used
> - Have a working Docker installation on your local system to allow you to use containers
> - Understand how to use existing Docker containers for common tasks
> - Be able to build your own Docker/Singularity containers by understanding both the role of a Dockerfile/Singularity recipe in building containers, and the syntax used in Dockerfiles/Singularity recipes
> - Understand how to manage Docker/Singularity containers on your local system
> - Appreciate decisions that need to be made around containerising research workflows
> - Understand the differences between Docker and Singularity containers and why Singularity is more suitable for multi-user systems (e.g. HPC)
> - Appreciate issues around reproducibility in software, understand how containers can address some of these issues and what the limits to reproducibility using containers are
{: .objectives}

The material on this site corresponds to Day 1 of the course - covering Docker. Day 2 of the course will look at Singularity and 
[the day 2 material is available on a separate site](https://epcced.github.io/2022-01-20_containers_online/).

> ## Prerequisites
>
> - You should have basic familiarity with using a command shell, and the lesson text will at times request that you "open a shell window", with an assumption that you know what this means.
>   - Under Linux or macOS it is assumed that you will access a `bash` shell (usually the default), using your Terminal application.
>   - Under Windows, Powershell and Git Bash should allow you to use the Unix instructions. We will also try to give command variants for Windows `cmd.exe`.
> - The lessons will sometimes request that you use a text editor to create or edit files in particular directories. It is assumed that you either have an editor that you know how to use that runs within the working directory of your shell window (e.g. `nano`), or that if you use a graphical editor, that you can use it to read and write files into the working directory of your shell.
{: .prereq}


{% include links.md %}

{% comment %}

<!--  LocalWords:  prereq links.md endcomment
 -->
{% endcomment %}
