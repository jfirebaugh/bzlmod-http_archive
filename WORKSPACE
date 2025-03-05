workspace(name = "bzlmod-http_archive")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rules_foreign_cc",
    sha256 = "4b33d62cf109bcccf286b30ed7121129cc34cf4f4ed9d8a11f38d9108f40ba74",
    strip_prefix = "rules_foreign_cc-0.11.1",
    urls = ["https://github.com/bazel-contrib/rules_foreign_cc/releases/download/0.11.1/rules_foreign_cc-0.11.1.tar.gz"],
)

load("@rules_foreign_cc//foreign_cc:repositories.bzl", "rules_foreign_cc_dependencies")

rules_foreign_cc_dependencies()
