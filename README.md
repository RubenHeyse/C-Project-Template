# C Project Template

Project structure sourced from [the CMake docs](https://cliutils.gitlab.io/modern-cmake/chapters/basics/structure.html)

## Folder Descriptions

1. `cmake`: CMake helper functions
2. `include`: Header files

   1. These should be seperated by context:

      ```txt
      include
      |-project
      |-|-lib.h
      |-device
      |-|-sensor
      |-|-|-driver.h
      |-|-MCU
      |-|-|-HAL
      ```
3. `src`: Project source files
4. `tests`: Unit and integration test source code
5. `docs`: Project documentation
6. `extern`: Contains git submodules almost exclusively
7. `scripts`: Helper scripts in any language
