mard
====

A manly language


Points
------

* It's a clojure.
* Clojure is a hosted language.
* mard will be optionally hosted on a native llvm language.
* Primary languages to keep in mind is: c, c++, go. Specially **C++**.
* The default namespace system of clojure is aweful. It must go away. The replacements candidates are CommonJs and go's system.
* Many ideas must be taken from other languages:
  - D's ranges
  - D's ranges
  - D's ranges
  - D's versioning, and unittesting
  - D's RAII
  - Ruby's standard library
  - Ruby's funness!
  - Ruby's dsl friendliness
  - Ruby's blocks
  - Scala's syntax customizablity
  - etc.
* Clojure's main ideas about how to host in another language are briliant. Those need to be curated and enhanced.
* mard's code generator can optionally retarget wich language it is hosting in.
* mard is a lisp. So it has a fantastic REPL. (You might want to take a look at ruby's PRY, and IPython)
* It is primarily JITed and compiled. It must be native grade. that is, it's in a margin of 20% of equivalent C code.
* By utilizing D's fantastic abstraction of ranges, and building on top of it, ideas like CSP, streams, RxExtentions, messaging, etc. a performant concurrency and paralelization is not far fetched goal.
