# cmake-gtest-official-samples

使用 CMake + gtest 官方例子建立项目，方便学习。

## 用法

    $ git clone https://github.com/fifilyu/cmake-gtest-official-samples.git
    $ mkdir cmake-gtest-official-samples_build
    $ cd cmake-gtest-official-samples_build
    $ cmake ../cmake-gtest-official-samples
    $ make -j 4
    $ make test
    
## 官方说明

>Google C++ Testing Framework Samples
>
> If you're like us, you'd like to look at some Google Test sample code. The [samples folder] has a number of well-commented samples showing how to use a variety of Google Test features.
> 
>    [Sample #1] shows the basic steps of using Google Test to test C++ functions.  
>    [Sample #2] shows a more complex unit test for a class with multiple member functions.  
>    [Sample #3] uses a test fixture.  
>    [Sample #4] is another basic example of using Google Test.  
>    [Sample #5] teaches how to reuse a test fixture in multiple test cases by deriving sub-fixtures from it.  
>    [Sample #6] demonstrates type-parameterized tests.  
>    [Sample #7] teaches the basics of value-parameterized tests.  
>    [Sample #8] shows using Combine() in value-parameterized tests.  
>    [Sample #9] shows use of the listener API to modify Google Test's console output and the use of its reflection API to inspect test results.  
>    [Sample #10] shows use of the listener API to implement a primitive memory leak checker.  

[samples folder]: http://code.google.com/p/googletest/source/browse/#svn/trunk/samples
[Sample #1]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample1_unittest.cc
[Sample #2]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample2_unittest.cc
[Sample #3]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample3_unittest.cc
[Sample #4]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample4_unittest.cc
[Sample #5]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample5_unittest.cc
[Sample #6]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample6_unittest.cc
[Sample #7]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample7_unittest.cc
[Sample #8]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample8_unittest.cc
[Sample #9]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample9_unittest.cc
[Sample #10]: http://code.google.com/p/googletest/source/browse/trunk/samples/sample10_unittest.cc

整理自 [Google C++ Testing Framework Samples](https://code.google.com/p/googletest/wiki/Samples)