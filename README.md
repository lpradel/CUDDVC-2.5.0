CUDDVC-2.5.0
============
------------

This is a Windows port of the latest version (**2.5.0, Jan 2013**) of the
popular C/C++ BDD/ADD/ZDD framework CUDD (*CU Decision Diagram Package*) by
Fabio Somenzi.

CUDD is available for free at [Fabio's website][^fn-cudd].

This project is tailored specifically for Microsoft Visual Studio 2012 and
compatibile with x64 machines in particular (however you need to make the
x64 adjustments in VS2012 yourself). I may decide to provide solutions for
previous versions of VS if there is enough interest.

[^fn-cudd]: http://vlsi.colorado.edu/~fabio/CUDD/

How to use CUDDVC-2.5.0
-----------------------
-----------------------

1. Clone the repo.
2. Open CUDDVC-2.5.0.sln in Visual Studio 2012.
3. Build the solution in Debug and Release mode.
4. When using CUDD in a project, add the include dir of CUDDVC-2.5.0 to your
   additional include directories in the project settings. Furthermore, add
   the directory where you keep the generated .lib files to your linker and
   include the debug and release version respectively.



*Have fun with CUDD!*