package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = [
        "doc.go",
        "keystone.go",
    ],
    tags = ["automanaged"],
    deps = [
        "//pkg/auth/user:go_default_library",
        "//pkg/util/cert:go_default_library",
        "//pkg/util/net:go_default_library",
        "//vendor:github.com/golang/glog",
        "//vendor:github.com/rackspace/gophercloud",
        "//vendor:github.com/rackspace/gophercloud/openstack",
    ],
)
