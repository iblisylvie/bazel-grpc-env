package(default_visibility = ["//visibility:public"])

load("@org_pubref_rules_protobuf//cpp:rules.bzl", "cc_proto_library")

filegroup(
    name = "protos",
    srcs = ["helloworld.proto", "common.proto"],
)

cc_proto_library(
    name = "grpc_lib",
    protos = [":protos"],
    verbose = 0,
    with_grpc = True,
)
