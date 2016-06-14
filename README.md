# whiteboard
whiteboard is a language for implementing solutions on real whiteboard

Whiteboard language is a C-like language designed to encode most the conventions used during coding sessions on physical whiteboard during interviews. It doesn't have a compiler only a human based interpreter where exact flow is agreed on by all participating parties. It has implicit garbage collector and unlimited amount of memory. Only single thread execution is supported in first version.

## types
Only following types are supported:
 - int
 - bool
 - array
 - String
 - user defined class

All fields in a class are public and can be accessed directly. Reasonable constructor is implicitly defined.

# functions
Even the language modeled from Java functions are allowed. Implicitly they are public static.

'result' is a special variable. If declared it will be used as returned value at the end of function.

# syntax
All semicolons are optional even in places where lack of one leads to ambiguity. In this case most reasonable case will chosen by the interpreter. This rule apply to other cases of ambiguity.

# recursion
TCO is supported. Stack size is reasonably large.

# library
Standard library represents all variations of all existing standard libraries including future ones. All typos are resolved reasonably (see above).

# context
Verbal expressions play a role of execution context which injects working code in arbitrary places in the whiteboard. The interpreter  must take it in account in addition to a photo of main program.
