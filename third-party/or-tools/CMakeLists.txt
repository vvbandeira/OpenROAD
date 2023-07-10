include(FetchContent)
FetchContent_Declare(
  or-tools
  # DOWNLOAD_EXTRACT_TIMESTAMP TRUE
  GIT_REPOSITORY https://github.com/google/or-tools.git
  GIT_TAG        v9.6
)

set(CMAKE_BUILD_TYPE Release)
set(BUILD_DEPS ON)
set(BUILD_CXX_EXAMPLES ON)
set(BUILD_CXX_SAMPLES OFF)
set(BUILD_EXAMPLES OFF)
set(BUILD_FLATZINC OFF)
set(BUILD_SAMPLES OFF)
set(BUILD_SHARED_LIBS OFF)

FetchContent_MakeAvailable(or-tools)
