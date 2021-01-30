# Course Notes for DATA 690
## Assignment 1

**Author**: Abeerah Qadir

**Date**: Jan 31 2021

### Python Basics
**Python** is an interpreted language.  The Python interpreter runs a program by executing one statement at a time.
Those doing data analysis or scientific computing make use of **IPython**, an enhanced Python interpreter, or Jupyter notebooks, web-based code notebooks.

**Jupyter *Notebook*,** a type of interactive document for code, text (with or without markup), data visualizations, and other output. 

**Extension .ipynb** - a self-contained file format that contains all of the content (including any evaluated code output) currently in the notebook. 

**Tab Completion** - While entering expressions in the shell, pressing the Tab key will search the namespace for any variables (objects, functions, etc.) matching the characters you have typed so far.
  *Combined with %Run* & *function key-word arguments*
  
 **Introspection** - Using a question mark (?) before or after a variable will display some general information about the object

**%run Command** - You can run any file as a Python program inside the environment of your IPython session using the %run command. 
 ***%run ipython_script_test.py*** - The script is run in an empty namespace (with no imports or other variables defined) so that the behavior should be identical to running the program on the command line using python script.py.

**Execute code from clipboard** - You can copy and paste code into any code cell
and execute it.
***%paste*** - takes whatever text is in the clipboard and executes it as a single block in the shell
***%cpaste*** - similar but gives you a special prompt for pasting code into
