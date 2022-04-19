sh_binary(
    name = "clang_tidy",
    srcs = ["run_clang_tidy.sh"],
    data = ["//:clang_tidy_config", "@llvm//llvm:bin/clang-tidy"],
    tags = ["no-sandbox"],
    visibility = ["//visibility:public"],
)
