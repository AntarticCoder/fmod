# FMOD

This repository contains the includes and macos libraries for FMOD.

## CMake

```cmake
find_library(
    FMOD_LIBRARY
    NAMES fmod
    PATHS #FMOD DIRECTORY
)

target_include_directories(Spear PRIVATE 
    #FMOD DIRECTORY
)

target_link_libraries(Target PRIVATE ${FMOD_LIBRARY})
```