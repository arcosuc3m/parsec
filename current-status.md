# Supported compilers

Currently supported compilers are:

  * GCC: Versions 5, 6, 7, 8, 9, 10
  * Clang: Clang 13 with some constraints

## Constraints in Clang Compiler

### Configurations not supported in Clang

  * **TBB** configuration: The reason is that the version of TBB embedded in the PARSEC distribution explictly does not support clang under Linux.

### Bundled ibraries not supported in Clang

  * **mesa**: Current version uses inline assembly code that is not valid for clang.
  * **tbb**: Current version has checks against Linux+clang configuration.
  * **parmacs**: Which package is using parmacs?

### Applications not supported in Clang

  * **facesim**: Templates issues with clang compiler.
  * **raytrace**: Depends on **mesa** that is not cupported with clang configurations.