# General computing tips

## Data
See https://www.sas.upenn.edu/~vr0j/econ8185-13/datadoc1.pdf for a good list of standard microdata sources and how to get them.

## Suggestions for small projects
1. Use comments
2. Use sensible variable names
3. Consider tests. Check if the output of a section is reasonable 

## Suggestions for large projects
1. Use functions. Functions should be small and have a clear purpose
2. Organize code into files
3. Use formal tests(see Unit Testing on Wikipedia). This is easy in Julia.
4. Consider version control (git). It is a little inconvenient to start using, but may help 
a lot if the project grows large. It allows you to work on a new feature in one branch, but maintain 
the working master for other work or comparison. The entire project history is recorded, so you can revert to any previous state if you need to.
