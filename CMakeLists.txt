cmake_minimum_required (VERSION 3.0.0)
enable_testing()

project (cpp-pre-type_traits)

# Unit testing
if (UNIT_TESTS)
  enable_testing()
  add_subdirectory(test)
endif()
