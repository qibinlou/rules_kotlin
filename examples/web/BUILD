package(default_visibility = ["//visibility:public"])

load("//kotlin:rules.bzl", "kotlin_js_library")

kotlin_js_library(
    name = "user",
    srcs = ["User.kt"],
    verbose = 2
    # args = ["-module-kind=umd", "-metainfo"]
)

kotlin_js_library(
    name = "main",
    srcs = ["main.kt"],
    deps = [
        ":user"
    ]
)