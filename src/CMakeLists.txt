set(SRC_X    DomainGridType.f90
             EnergyGridType.f90
             ForcingType.f90
             RunModule.f90
             UtilitiesModule.f90
             WaterType.f90
             CACHE INTERNAL "")

set(SRC_MODS AlbedoModule.f90
             AtmProcessing.f90
             AttributesType.f90
             CMakeLists.txt
             CanopyWaterModule.f90
             ConstantsModule.f90
             DateTimeUtilsModule.f90
             DevNotes.txt
             DomainType.f90
             DomainGridType.f90
             EnergyModule.f90
             EnergyGridType.f90
             EnergyType.f90
             ErrorCheckModule.f90
             EtFluxModule.f90
             ForcingType.f90
             ForcingGridType.f90
             ForcingModule.f90
             InterceptionModule.f90
             LevelsGridType.f90
             LevelsType.f90
             NamelistRead.f90
             OptionsGridType.f90
             OptionsType.f90
             ParametersGridType.f90
             ParametersRead.f90
             ParametersType.f90
             PrecipHeatModule.f90
             ShortwaveRadiationModule.f90
             SnowLayerChange.f90
             SnowSoilTempModule.f90
             SnowWaterModule.f90
             SnowWaterRenew.f90
             SoilWaterModule.f90
             SoilWaterMovement.f90
             SoilWaterRetentionCoeff.f90
             SubsurfaceRunoffModule.f90
             SurfaceRunoffInfiltration.f90
             SurfaceRunoffModule.f90
             ThermalPropertiesModule.f90
             UtilitiesModule.f90
             WaterGridType.f90
             WaterModule.f90
             WaterType.f90
             CACHE INTERNAL "")
add_library(srcx "${SRC_X}")
add_library(src "${SRC_MODS}")
