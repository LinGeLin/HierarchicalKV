load("@local_config_cuda//cuda:build_defs.bzl", "cuda_cc_library")

cuda_cc_library(
    name = "types_and_utils",
    srcs = [
    ],
    hdrs = [
        "types.cuh",
        "utils.cuh",
    ],
    visibility = [
        "//visibility:public",
    ],
    deps = [
        "@local_config_cuda//cuda",
    ],
)

cuda_cc_library(
    name = "merlin",
    srcs = [
    ],
    hdrs = [
        "allocator.cuh",
        "array_kernels.cuh",
        "core_kernels.cuh",
        "debug.hpp",
        "flexible_buffer.cuh",
        "group_lock.cuh",
        "memory_pool.cuh",
        "optimizers.cuh",
    ],
    visibility = [
        "//visibility:public",
    ],
    deps = [
        "//include/merlin:types_and_utils",
        "//include/merlin/core_kernels",
        "@local_config_cuda//cuda",
    ],
)
