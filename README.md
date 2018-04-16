# simple-cmake
  A simple module based cmake project with api-lib, examples and source modules.

## To build the example:
  ```bash
  # Checkout project
  git clone https://github.com/plopp/simple-cmake.git && cd simple-cmake

  # Create out-of-source build dir
  mkdir build && cd build

  # Create makefiles
  cmake ../ -DCMAKE_BUILD_TYPE=Debug

  # Make the project
  make

  # Execute the example
  ./example/example

  ```

## TODO-list:
  * Add install directives.
  * Add cmake export directives to export install information.
  * Add doxygen generation.
  * Add GTest tests.
  * Add version handling with hash+dirty git.
  * Support private headers in modules and prevent them from being included in the public api.
  * Add cpack support.
