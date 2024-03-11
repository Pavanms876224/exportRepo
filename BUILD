# Load the necessary Bazel rules
load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
	name = "myExportLib",
	srcs = ["libmylib.a"],
    hdrs = ["inc/ara/lib.h"],
	copts = ["-Iinc"],
    visibility = ["//visibility:public"]
	)