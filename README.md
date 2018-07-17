
# Installing CPLEX 12.8 on Windows and Mac OS for Python usage

This is for Python usage.

## For Windows

### Installing CPLEX
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

CPLEX>   quit

```


1. Install docplex python package

* For Anaconda Navigator
	* Go to Environnement
	* Start a terminal from the **base** 
	* Follow https://anaconda.org/IBMDecisionOptimization/docplex

```

(base) C:\Users\IBM_ADMIN>conda install -c ibmdecisionoptimization docplex
Solving environment: done

```

* For pip package manager

TBD

1. Check the following provided code is working

TBD

**Done**

## For MacOS

TBD


