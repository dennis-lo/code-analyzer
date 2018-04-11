# code-analyzer
An analyzer that evaluate code and provide suggestions

The development of this analyzer should be divided into the following phases (to be revised):

0. Clean-up
  - Trailing whitespace
  - Style

1. Statement-level analysis
  - Dead statements
  - Simplification
  - Readibility

2. Block-level analysis
  - Repeated lines of code / patterns
  - Comparison / flow control

3. Function-level analysis
  - Reduce recursion
  - Modularity

4. Basic, code efficiency analysis
  - Static components, string comparison, string construction, etc.

5. Pattern-level analysis
  - Dependency between roles (objects)
  - Not necessarily applicable to some programming language

Target:
- This analyzer should support the following programming / scripting languages:
  - Java
  - Tcl script
  - Javascript

Configuration / Inheritance:
- This analyzer should be configurable or extend-able to support different programming / scripting languages.
- The effort of supporting an additional language should be reduced to configuration and / or enhancement to existing modules with minimal coding involved.

Implementation:
- C++?
- Java?
- Tcl script?
- To be determined

Front-end framework:
- GTK+?
- Tk?
- To be determined

Installation, execution, etc.
