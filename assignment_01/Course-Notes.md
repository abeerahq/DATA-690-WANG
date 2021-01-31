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

**Magic Commands** -  any command prefixed by the percent symbol %. They are designed to facilitate common tasks and enable you to easily control the behavior of the IPython system.

**%matplotlib** sets up the integration so you can create multiple plot windows without interfering with the console session

### Language Semantics

Python uses whitespace (tabs or spaces) to structure code instead of using braces as in
many other languages

**Colon** denotes the start of an indented code block after which all of the code must
be indented by the same amount until the end of the block

**Everything is an object** - Every number, string, data structure, function, class, module, and so on exists in the Python interpreter in its own “box” = *Python Object*

**Comments** - Pound sign (#) before text is used to add comments to code.

**Reference** - When assigning a variable (or name) in Python, you are creating a reference to the object on the righthand side of the equals sign.

**Variables** - names for objects within a particular namespace; the type information is
stored in the object itself.

**Duck Typing** - Often you may not care about the type of an object but rather only whether it has certain methods or behavior.

**Module** - a file with the .py extension containing Python code.

**Mutable objects** -  means that the object or values that they contain can
be modified

**Immutable** - like strings and tuples

**Scalar** - numerical data, strings, boolean (True or False) values, and dates and time. These “single value” types are sometimes called scalar types.

**String literals** -  using either single quotes ' or double quotes ". For multiline strings you can use triple quotes ' ' ' or " " ": 

**Slicing** - syntax s[:3]

**Escape character** - backslash character \, s used to specify special characters like newline \n or Unicode characters.

**None** - is the Python null value type.

**Control Flow** - Python has several built-in keywords for conditional logic, loops, and other standard control flow concepts. 

**if statement** - checks a condition that, if True, evaluates the code in the block that follows

**for loops** - do something with value.  while loop specifies a condition and a block of code that is to be executed until the condition evaluates to False or the loop is explicitly ended with break.

**pass** - can be used in blocks where no action is to be taken (or as a placeholder for code not yet implemented)

**Ternary expression** - allows you to combine an if-else block that produces a value into a single line or expression


