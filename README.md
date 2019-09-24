# Overview

## Introductory Python

### Getting Started

.|Python|C++|Java
--|-----|---|----
Typing|Strong|Weak|..
Typing|Dynamic|Sttic|..
FCF| Yes|No|..
Garbage Collection|Yes|No
Interpreted|Yes|No

### The Good
* Dynamic/Duck Typing
* Garbage Collection
* Interpreted

### The Bad
* Dynamic/Duck Typing
* Garbage Collection (Object overhead)
* Interpreted

### Python Hello World

```Python
def hello_world():
  print("Hello World")

def greater_than(x, y):
  if x > y:
    return x
  else:
    return y
```

### Data Types
- Basic types
  - Integers/Floats/Complex (mutability/caching)
- Sequence types
  - Strings (slicing)
  - Lists vs Tuples
- Associative types
  - Dictionaries (immutable keys)
  - Sets

### Functions
- Control Flow
  - Conditional branching
  - else on loops
- Scope (LEGB{nonlocal,global}/leaky)
  - Scope vs Block (3 scoping units, several blocking units)
- First class functions
- Positional/keyword/default args/*Args/\*\*kwargs

### Modules
- \_\_name\_\_
- Importing and the module hierarchy (dot)
- collections


## Intermediate Python

### Decorators

### Classes

* class/instance variables
* class/instance methods
* static methods
* getters/setters/deleters

### Dunder Methods

* airthmetic protocol
* comparison protocol
* print protocol
* iteration protocol
* slicing protocol
* context management protocol (originally a whole section on this)

### Inheritance

* basic inheritance
* multiple inheritance and MRO
* diamond problem

### Python internals

* a.x == a.\_\_dict\_\_['x']
* bytecode and interpretation

## Testing in Python

* pytest basics
* parameterization/fixtures
* xskip/xfail
* mocking and monkeypatching

### Basics

### params

### Parameterization /(xskip/xfail/xparam)

## Logging in Python

### Logging Basics

### Complete Logging
- Loggers
- Handlers
- Formatters
- Filters
- Logging Hierarchy
