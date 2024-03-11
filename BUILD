# Load the necessary Bazel rules
load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
	name = "myExportLib",
	srcs = ["libmylib.a"],
    hdrs = ["lib.h"],
    visibility = ["//visibility:public"]
	)