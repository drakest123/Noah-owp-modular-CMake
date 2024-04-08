set(D_MODS AsciiReadModule.f90
           OutputModule.f90
           CACHE INTERNAL "")
add_library(driver "${D_MODS}")
target_link_libraries(noah-owp-modular driver bmix bmi src)
#target_link_libraries(noah-owp-modular bmi)
#target_include_directories(noah-owp-modular PUBLIC $<TARGET_PROPERTY:bmi,Fortran_MODULE_DIRECTORY>)
