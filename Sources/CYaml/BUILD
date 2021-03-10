load(
    "@rules_cc//cc:defs.bzl",
    "objc_library"
)

objc_library(
  name = "CYaml",
  enable_modules = True,
  srcs = glob([
    "src/*.c",
    "src/*.h",
  ]),
  module_map = "include/module.modulemap",
  hdrs = glob([
    "include/*.h",
  ]),
  includes = ["include"],
  visibility = ["//visibility:public"]
)
