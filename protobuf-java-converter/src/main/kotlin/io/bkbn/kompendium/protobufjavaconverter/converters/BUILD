load("@io_bazel_rules_kotlin//kotlin:jvm.bzl", "kt_jvm_library")

kt_jvm_library(
    name = "converters",
    srcs = ["FieldDescriptiorConverters.kt"],
    visibility = ["//visibility:public"],
    deps = [
        "@maven//:io_bkbn_kompendium_json_schema",
        "@maven//:com_google_protobuf_protobuf_java"
    ],
)
