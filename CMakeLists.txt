project(TestProject)

add_executable(TestProject
src/Test.cpp)

add_subdirectory(external/SubmoduleTest)

target_link_libraries(SubModuleTagTest)