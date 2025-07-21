-Internal working of python:
 Step 1: Compile to Byte code(Compiled down). (not getting compile to byte code)
          Byte code is low level code and platform inde0pendent.
          Byte code runs faster.

    .pyc---> Compiled python (Frozen Binaries)
    __pycache__ ---->  Changes/Updates in the code reconstructs the .pyc files by deleting/completely replacing the .pyc files.
    System folder.
    Source change and Python version (prog. languages uses diffing algorithm to chek which part is available)
    - hello _proj.cpython-312.pyc      
    Works only for imported files
    Not for top level files.
 Step 2: Python Virtual Machine (PVM)
    - Code loop to iterate Byte code.
    - Run time Engine.
    - Also known as python interpreter.

Byte code is not machine code.
- It is a python specific interpretation.
- cpython(Standard Implementation), jpython(java ki binaries ke sath), IronPython, Stackless(For working in concurrency),PyPy(for performance)

