load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "build_bazel_rules_swift",
    sha256 = "2ce874c8c34a03a0a33bfb0c8100f0be32279e0a40f5b794fd943f15441e034a",
    url = "https://github.com/bazelbuild/rules_swift/releases/download/1.3.0/rules_swift.1.3.0.tar.gz",
)

load(
    "@build_bazel_rules_swift//swift:repositories.bzl",
    "swift_rules_dependencies",
)

swift_rules_dependencies()

load(
    "@build_bazel_rules_swift//swift:extras.bzl",
    "swift_rules_extra_dependencies",
)

swift_rules_extra_dependencies()
