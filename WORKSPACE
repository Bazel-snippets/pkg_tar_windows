load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

http_archive(
    name = "rules_python",
    sha256 = "b5668cde8bb6e3515057ef465a35ad712214962f0b3a314e551204266c7be90c",
    strip_prefix = "rules_python-0.0.2",
    url = "https://github.com/bazelbuild/rules_python/releases/download/0.0.2/rules_python-0.0.2.tar.gz",
)

git_repository(
    name = "rules_pkg",
    commit = "66f92ebb6b2af31be8d0d8262ecb8f1a674727fb",
    remote = "https://github.com/bazelbuild/rules_pkg.git",
    shallow_since = "1601495934 -0400",
    strip_prefix = "pkg",
)
