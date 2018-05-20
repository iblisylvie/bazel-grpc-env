package(default_visibility = ["//visibility:public"])

cc_binary(
    name = "client",
    srcs = ["greeter_client_main.cc"],
    deps = [":clientlib"],
)

cc_binary(
    name = "server",
    srcs = ["greeter_server.cc"],
    deps = ["//proto:grpc_lib"],
)

cc_library(
    name = "clientlib",
    srcs = ["greeter_client.cc"],
    hdrs = ["greeter_client.h"],
    deps = ["//proto:grpc_lib"],
)
