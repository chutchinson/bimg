load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

local_repository(
    name = "astc_codec",
    path = __workspace_dir__ + "/3rdparty/astc-codec"
)

git_repository(
    name = "bx",
    remote = "https://github.com/chutchinson/bx.git",
    commit = "dc07a5253d685b2de09fae00a70ff8dcbfcdb462", 
    shallow_since = "1581053004 -0500"
)