
# Using Python with CPLEX 12.8 on Windows and Mac OS

This gives instruction to install the library docplex.

## On Windows

### Installing Docplex
1. Ensure that : 
  CPLEX_studio128\cplexdir\bin\cplex\bin\x64_win64
  CPLEX_studio128\cpoptimizer\bin\x64_win64
  are in the PATH variable. CPLEX_studio128 stands for your installation dir.
  
1. Check by starting successfully cplex and cpoptimizer 
  from the command line. 
  
```
C:\Users\IBM_ADMIN>cplex

Welcome to IBM(R) ILOG(R) CPLEX(R) Interactive Optimizer 12.8.0.0
  with Simplex, Mixed Integer & Barrier Optimizers
5725-A06 5725-A29 5724-Y48 5724-Y49 5724-Y54 5724-Y55 5655-Y21
Copyright IBM Corp. 1988, 2017.  All Rights Reserved.

Type 'help' for a list of available commands.
Type 'help' followed by a command name for more
information on commands.

CPLEX> quit

```

1. Install docplex python package

* With Anaconda Navigator
	* Go to Environnement
	* Start an **Anaconda terminal** from the **base** 
	* Follow instruction at https://anaconda.org/IBMDecisionOptimization/docplex

```
(base) C:\Users\IBM_ADMIN>conda install -c ibmdecisionoptimization docplex
Solving environment: done
```

* With pip package manager

```
pip install docplex
```
2. Set up docplex so that python cplex codes run locally.

Define the *PYTHONPATH* environment variable

```
set PYTHONPATH=YOURCPLEXINSTALLDIR\cplex\python-version\x64_win64

```
- yourcplexinstalldir being the install dir set with the installer.
- python-version being 2.7, 3.5 or 3.7


**Done**

## On MacOS

TBD


