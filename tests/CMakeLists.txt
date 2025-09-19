add_executable(test-hello test-hello.cpp)
target_link_libraries(test-hello PUBLIC basic)
add_test( NAME test-hello COMMAND test-hello)
 

add_executable(test-version test-version.cpp)
target_link_libraries(test-version PUBLIC basic)
add_test( NAME test-version COMMAND test-version)