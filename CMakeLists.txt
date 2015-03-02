cmake_minimum_required(VERSION 2.6)

PROJECT (cmake-gtest-official-samples)

ADD_SUBDIRECTORY(test)

enable_testing()
add_test(NAME sample1_unittest COMMAND sample1_unittest)
add_test(NAME sample2_unittest COMMAND sample1_unittest)
add_test(NAME sample3_unittest COMMAND sample1_unittest)
add_test(NAME sample4_unittest COMMAND sample1_unittest)
add_test(NAME sample5_unittest COMMAND sample1_unittest)
add_test(NAME sample6_unittest COMMAND sample1_unittest)
add_test(NAME sample7_unittest COMMAND sample1_unittest)
add_test(NAME sample8_unittest COMMAND sample1_unittest)
add_test(NAME sample9_unittest COMMAND sample1_unittest)
add_test(NAME sample10_unittest COMMAND sample1_unittest)
