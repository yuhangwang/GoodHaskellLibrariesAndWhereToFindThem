# GoodHaskellLibrariesAndWhereToFindThem
A list of good (useful) Haskell libraries 


## Emededable Haskell Interpreter
* [hint](https://github.com/mvdan/hint)
  - Features:
    - load Haskell modules
    - type-check and evaluate strings and convert them to values
    - type-safe
    - thread-safe
    
* [dyre](https://github.com/willdonnelly/dyre)
  Dynamic reconfiguration library
  - Features
    - dynamically recompling Haskell programs with new configurations
    
* [mueval](https://github.com/gwern/mueval)
  A standalone Haskell interpreter
  - Features
    - can load definitions from files


## FFI (foreign language interface)
* [call-haskell-from-anything](https://github.com/nh2/call-haskell-from-anything) (**MIT License**)  
  Use [MsgPack](http://msgpack.org) format to encode/decode function call argument   
  and return values to and from compiled Haskell dynamic libries.   
  Implementation of `MsgPack` are available in at least the following languages
  - [JavaScript (NodeJS)](https://github.com/creationix/msgpack-js) (MIT license)
  - [Python](https://pypi.python.org/pypi/msgpack-python) (Apache license)
  - [Julia](https://github.com/kmsquire/MsgPack.jl) (MIT license)
  - [Lua](https://github.com/fperrad/lua-MessagePack) (MIT license)
  - [Scala](https://github.com/msgpack/msgpack-scala) (Apache 2.0 license)
  - [Java](https://github.com/msgpack/msgpack-java) (Apache 2.0 license)
  - [C/C++](https://github.com/msgpack/msgpack-c) (Boost 1.0 license)
  - [D](https://github.com/msgpack/msgpack-d) (Boost 1.0 license)
  - [C#](https://github.com/msgpack/msgpack-cli) (Apache 2.0  license)
  - [Tcl](https://github.com/jdc8/msgpack) (BSD-3 license)
  - [Go](https://github.com/ugorji/go-msgpack) (BSD-3 license)
  - [Ruby](https://github.com/msgpack/msgpack-ruby) (Apache 2.0 license)
  
