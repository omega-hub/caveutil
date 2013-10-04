# caveutil depends on cyclops
set(MODULES_cyclops true CACHE BOOL " " FORCE)
# create this variable to trigger a CMake re-generate step
set(caveutil_REGENERATE_TRIGGER true CACHE INTERNAL)