set(D_MODS AsciiReadModule.f90
           OutputModule.f90
           CACHE INTERNAL "")
add_library(driver "${D_MODS}")
