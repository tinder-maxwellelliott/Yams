load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "Yams",
    srcs = glob(["*.swift"]),
    defines = ["SWIFT_PACKAGE"],
    module_name = "Yams",
    deps = ["//Sources/CYaml:CYaml"],
    visibility = ["//visibility:public"]
)
