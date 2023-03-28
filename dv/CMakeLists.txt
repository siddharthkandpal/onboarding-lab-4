find_package(Catch2 3 REQUIRED CONFIG)
add_executable(tests)
target_sources(tests PRIVATE 
exercise1.cpp exercise2.cpp exercise3.cpp exercise4.cpp)
nyu_link_sv(tests PRIVATE lab4)
