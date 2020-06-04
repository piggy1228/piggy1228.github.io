---
title: "PennOS (C)"
excerpt: "Implemented a User-level UNIX-like Operating System"
collection: project
description: "Built a simple shell to execute commands based on a  User-level UNIX-like Operating System"


---
Project report are available [<u>here</u>](https://piggy1228.github.io/files/pennOS.pdf)
* Implemented a User-level UNIX-like Operating System.
* A simple shell booted on PennOS simulator supported the following features: foreground and background pro-
cesses with job control; synchronous child waiting; a complement of built-in functions, e.g., cat, nice, sleep, etc.;
and redirection with truncation and append modes.
* PennOS ran as a single process on a host OS, while using ucontext library to implement a basic Round Robin
priority scheduler to simulate multiprocessing.
