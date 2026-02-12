# CMake snippet for building the host-side tools.
project(CFETOOLS C)

# Ground System command utility not needed for unit testing
# Commented out to avoid requiring cFS-GroundSystem submodule
# add_subdirectory(cFS-GroundSystem/Subsystems/cmdUtil)
add_subdirectory(elf2cfetbl)
add_subdirectory(tblCRCTool)

