set(BMI_X    bmi_noahowp.f90
             ../src/RunModule.f90
             CACHE INTERNAL "")
set(BMI_MODS bmi.f90
             bmi_grid.f90
             CACHE INTERNAL "")
add_library(bmix "${BMI_X}")
add_library(bmi "${BMI_MODS}")
add_dependencies(bmix srcx)
target_link_libraries(bmix bmi driver src)
