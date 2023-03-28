find_package(Catch2 3 REQUIRED CONFIG)
add_executable(tests)
target_sources(tests PRIVATE tests.cpp)
nyu_link_sv(tests PRIVATE lab4)
