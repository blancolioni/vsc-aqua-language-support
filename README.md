# Aqua Language Support

This Visual Studio Code extension provides syntax highlighting and code snippets for Aqua language development.

Once installed, files with the .aqua extension will automatically activate the Aqua syntax highlighting and snippet
support.

Aqua is the extension language for the [Aquarius](https://github.com/blancolioni/aquarius) ebnf compiler.
It is a dialect of [Eiffel](https://www.eiffel.org/).
The most significant change is that classes are now hierarchical.

This is a fork of the wonderful [Eiffel extension](https://github.com/szeredniklaszlo/vsc-eiffel-language-support) 
by [szeredniklaszlo](https://github.com/szeredniklaszlo).

## Syntax Highlighting

The Aqua language syntax is supported through a custom grammar definition. It highlights the following:

- Comments: Single-line comments start with `--`.
  Keywords: Keywords such as `class`, `feature`, `do`, `end`, `if`, `else`, `from`, and more are highlighted.
- Variables: All variable names that follow standard Eiffel naming conventions are highlighted.
- Constants: Common constants like `True`, `False`, `Void`, `Result`, and `Current` are included.
- String Literals: Double-quoted strings are highlighted, with escape sequences recognized within them.
- Numbers: Numeric constants are highlighted.
  Modifiers: Keywords like `deferred`, `expanded`, and storage modifiers are highlighted for better readability.
- Class Definitions: The extension provides recognition for class structures, including inheritance and class-level
  declarations.

## Code Snippets

**C# / Java keywords** for snippets, just write the familiar keywords from your mind, and press tab.

### Variables:

- var
- null_var
- const

### Assignments / conversions:

- assignment
- cast
- convert_from
- convert_to

### Functions:

- fun / routine
- once fun / once routine

### Branching and checks:
- if
- elif / elseif / else if

---

- switch / inspect
- case / when

---

- check
- instanceof / check type
- if not null / check not null
- if attached / check attached

---

- strip / only

### Loops:
- for / repeat
- foreach / across
- foreach all
- foreach some
- retry

### Exceptions:
- throw if null / throw if not attached / throw if detached

### Classes:
- class
- expanded class
- abstract class / deferrred class

#### Class instantiation:
- new statement / create statement
- new expression / create expression

#### Class variables:
- property
- attribute

#### Class functions:
- abstract fun / deferred routine
- export fun / external routine

---

- init attribute
- private features
- private creates
- private constructors
- protected features
- protected constructors
- protected constructors

### Other:
- debug
- indexing

## Enjoy coding in Aqua with enhanced productivity!
