set(the_description "Computational Photography")

if(HAVE_CUDA)
  ocv_warnings_disable(CMAKE_CXX_FLAGS -Wundef -Wmissing-declarations -Wshadow)
endif()

ocv_define_module(photo opencv_imgproc OPTIONAL opencv_cudaarithm opencv_cudaimgproc WRAP java python js)
