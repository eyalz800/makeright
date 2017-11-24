makeright
=========

* A simple yet generic and flexible makefile.

Architecture
------------

Split into 3 files:
* **makefile_project** - which source files to compile, with what flags, to what architectures - by default include directories are all 
directories named 'inc' or 'include' and the source directories is the directory named 'src'.
* **makefile_config** - which compiler to use, ideal for cross compilation settings.
* **makefile** - the generic logic, edit only on complex use cases.

Getting Started
---------------

1. Clone the project.
2. Create a 'src' directory.
3. Add your 'main.cpp' into 'src'.
4. Execute one of 'make', 'make mode=debug', 'make mode=release', and explore the directory tree.
5. Clean using 'make clean'.

**This documentation is incomplete, more to come soon**
