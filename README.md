# code-analyzer
An analyzer that evaluate code and provide suggestions

This analyzer should provide the following features (*to be revised*):

- Clean-up
	- Trailing whitespace
	- Style

- Statement-level analysis
	- Dead statements
	- Simplification
	- Readibility

- Block-level analysis
	- Repeated groups of code / patterns
	- Comparison / flow control

- Function-level analysis
	- Reduce recursion
	- Dependency between functions
	- Modularity

- Class-level analysis
	- Hidden fields, methods
	- Not necessarily applicable to some programming languages

- Basic, code efficiency analysis
	- Static components, string comparison, string construction, etc.

- Pattern-level analysis
	- Dependency between roles (objects)
	- Not necessarily applicable to some programming languages

**Target:**
- This analyzer should support the following programming / scripting languages:
  - Java
  - Tcl script
  - Javascript

**Configuration / Inheritance:**
- This analyzer should be configurable or extend-able to support different programming / scripting languages.
- The effort of supporting an additional language should be reduced to configuration and / or enhancement to existing modules with minimal coding involved.

**Implementation:**
- C++?
- Java?
- Tcl script?
- *To be determined*

Front-end framework:
- GTK+?
- Tk?
- *To be determined*

*Installation, execution, etc.*
