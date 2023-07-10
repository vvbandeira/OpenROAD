include(FetchContent)
FetchContent_Declare(
  or-tools
  # DOWNLOAD_EXTRACT_TIMESTAMP TRUE
  GIT_REPOSITORY https://github.com/google/or-tools.git
  GIT_TAG        v9.6
)
FetchContent_MakeAvailable(or-tools)
