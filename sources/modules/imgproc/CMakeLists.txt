set(the_description "Image Processing")
ocv_add_dispatched_file(accum SSE4_1 AVX AVX2)
ocv_add_dispatched_file(bilateral_filter SSE2 AVX2)
ocv_add_dispatched_file(box_filter SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(filter SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(color_hsv SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(color_rgb SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(color_yuv SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(median_blur SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(morph SSE2 SSE4_1 AVX2)
ocv_add_dispatched_file(smooth SSE2 SSE4_1 AVX2)
ocv_define_module(imgproc opencv_core WRAP java python js)
