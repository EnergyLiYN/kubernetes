package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
    "go_test",
)

go_library(
    name = "go_default_library",
    srcs = [
        "helpers.go",
        "types.go",
    ],
    tags = ["automanaged"],
    deps = ["//vendor:k8s.io/gengo/namer"],
)

go_test(
    name = "go_default_test",
    srcs = ["helpers_test.go"],
    library = "go_default_library",
    tags = ["automanaged"],
    deps = [],
)
