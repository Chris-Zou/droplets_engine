cmake_minimum_required( VERSION 3.12.0 ) # Latest version of CMake when this file was created.

add_subdirectory( DX_Tutorial )

set_target_properties (DX_Tutorial PROPERTIES
    FOLDER Samples
)