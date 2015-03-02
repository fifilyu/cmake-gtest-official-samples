ADD_EXECUTABLE(sample1_unittest gtest_main.cc sample1_unittest.cc ../src/sample1.cc)
TARGET_LINK_LIBRARIES(sample1_unittest gtest gtest_main)

ADD_EXECUTABLE(sample2_unittest gtest_main.cc sample2_unittest.cc ../src/sample2.cc)
TARGET_LINK_LIBRARIES(sample2_unittest gtest gtest_main)

ADD_EXECUTABLE(sample3_unittest gtest_main.cc sample3_unittest.cc)
TARGET_LINK_LIBRARIES(sample3_unittest gtest gtest_main)

ADD_EXECUTABLE(sample4_unittest gtest_main.cc sample4_unittest.cc ../src/sample4.cc)
TARGET_LINK_LIBRARIES(sample4_unittest gtest gtest_main)

ADD_EXECUTABLE(sample5_unittest gtest_main.cc sample5_unittest.cc ../src/sample1.cc)
TARGET_LINK_LIBRARIES(sample5_unittest gtest gtest_main)

ADD_EXECUTABLE(sample6_unittest gtest_main.cc sample6_unittest.cc)
TARGET_LINK_LIBRARIES(sample6_unittest gtest gtest_main)

ADD_EXECUTABLE(sample7_unittest gtest_main.cc sample7_unittest.cc)
TARGET_LINK_LIBRARIES(sample7_unittest gtest gtest_main)

ADD_EXECUTABLE(sample8_unittest gtest_main.cc sample8_unittest.cc)
TARGET_LINK_LIBRARIES(sample8_unittest gtest gtest_main)

ADD_EXECUTABLE(sample9_unittest sample9_unittest.cc)
TARGET_LINK_LIBRARIES(sample9_unittest gtest gtest_main)

ADD_EXECUTABLE(sample10_unittest sample10_unittest.cc)
TARGET_LINK_LIBRARIES(sample10_unittest gtest gtest_main)