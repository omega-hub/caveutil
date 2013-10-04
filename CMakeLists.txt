if(NOT MODULES_cyclops)
	# caveutil depends on cyclops
	set(MODULES_cyclops true CACHE BOOL " " FORCE)
	# create this variable to trigger a CMake re-generate step
	set(INTERNAL_REGENERATE_caveutil true CACHE BOOL "")
endif()