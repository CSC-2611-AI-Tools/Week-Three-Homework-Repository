# Week-Three-Homework-Repository
This is a repository dedicated to storing code that has been taken from homework two, which can be meant for future reference

## Assignment 4: Complexity and Benchmarking
Overview: Follow through the attached notebook to run and complete all cells.  Make sure you read the instructions to learn the steps 
(the goal isn't to complete it quickly but to learn the steps).  

## Profiling & Timing Code
In the process of developing code and creating data processing pipelines, there are often trade-offs you can make between various
implementations. Once you have your code working, it can be useful to dig into its efficiency a bit. Sometimes it's useful to check the 
execution time of a given command or set of commands; other times it's useful to dig into a multiline process and determine where the 
bottleneck lies in some complicated series of operations. 

## The IPython Magic Commands
`%time` : Time the execution of a single statement
`%timeit` : Time repeated execution of a single statement for more accuracy
`%prun` : Run code with the profiler
`%lprun` : Run code with the line-by-line profiler
`%memit` : Measure the memory use of a single statement
`%mprun` : Run code with the line-by-line memory profiler

The last four commands are not bundled with IPython–you'll need to get the line_profiler and memory_profiler extensions,
which we will discuss in the following sections