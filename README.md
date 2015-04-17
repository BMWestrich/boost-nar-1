boost-nar
=========

The Boost C++ libraries in maven form for producing Nar artefacts.

To install simply clone the repo and run:
  mvn install


The libraries are available as separate dependencies as per a typical module layout. This means if required you can depend only upon the boost filesystem module, the necessary transitive depedencies will be automatically available.


Things to note
-----------------

* iostreams does not use bzip TODO compiler flag or edited the code? We don't want to be changing boost.
* minor change to lexical-cast (converter_lexical_streams.hpp) to prevent error from running in visual studio environment

