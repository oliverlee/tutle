load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library (
    name = "fmt",
    defines = ["FMT_HEADER_ONLY"],
    hdrs = glob(["include/**/*"]),
    includes = ["include"],
    visibility = ["//visibility:public"],
)
