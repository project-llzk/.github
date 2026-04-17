# Overview

LLZK is an open-source Intermediate Representation (IR) for Zero Knowledge (ZK) circuit languages.
The LLZK project provides a flexible framework, inspired by LLVM, designed to unify diverse ZK front-end languages and backend ZK architectures.

# Project Organization

The core of LLZK is contained in [llzk-lib](https://github.com/project-llzk/llzk-lib) which defines the IR and passes for transformation, optimization, and analysis. It is written in C++ using MLIR, and it provides a C API for foreign language bindings. The lists below link to bindings for other programming languages, frontend ZK language translators, and backend targets for LLZK.

- Programming language bindings:
    - [C/C++](https://github.com/project-llzk/llzk-lib)
    - [Rust](https://github.com/project-llzk/llzk-rs)

- Frontends:
    - [circom](https://github.com/project-llzk/circom)
    - [Halo2/PLONKish](https://github.com/project-llzk/haloumi)
    - [airbender](https://github.com/project-llzk/airbender-llzk-frontend)

- Backends:
    - [R1CS](https://github.com/project-llzk/llzk-lib/tree/main/backends/r1cs)
    - [ZK Vanguard](https://docs.veridise.com/zkvanguard/)
    - [Picus](https://github.com/Veridise/pcl-mlir)
    - [zkLean](https://github.com/project-llzk/llzk-lib/tree/main/backends/zklean)


# Major Contributors

- [Veridise](https://github.com/Veridise/)
- [Ethereum Foundation](https://ethereum.foundation/)
- [Galois](https://github.com/GaloisInc)
