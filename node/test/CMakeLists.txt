set(test_srcs node_test.cpp session_test.cpp)
set(test_libs node)

add_gmock_test(node_tests)
