
load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_closure",
    sha256 = "5b00383d08dd71f28503736db0500b6fb4dda47489ff5fc6bed42557c07c6ba9",
    strip_prefix = "rules_closure-308b05b2419edb5c8ee0471b67a40403df940149",
    urls = [
        "https://storage.googleapis.com/mirror.tensorflow.org/github.com/bazelbuild/rules_closure/archive/308b05b2419edb5c8ee0471b67a40403df940149.tar.gz",
        "https://github.com/bazelbuild/rules_closure/archive/308b05b2419edb5c8ee0471b67a40403df940149.tar.gz",  # 20\

    ],
)

load("//third_party:repo.bzl", "tf_http_archive")

load("//core:workspace.bzl", "clean_dep")

tf_http_archive(
    name = "eigen_archive",
    build_file = clean_dep("//third_party:eigen.BUILD"),
    patch_file = clean_dep("//third_party/eigen3:gpu_packet_math.patch"),
    sha256 = "e81b91b22f1c7155deea4c457548ecdbd698cfed493444fceb7f9b5d797bb9a9",
    strip_prefix = "eigen-b9362fb8f76fbba805b56afbc0f5de0a279631b5",
    urls = [
        "https://storage.googleapis.com/mirror.tensorflow.org/gitlab.com/libeigen/eigen/-/archive/b9362fb8f76fbba805b56afbc0f5de0a279631b5/eigen-b9362fb8f76fbba805b56afbc0f5de0a279631b5.tar.gz",
        "https://gitlab.com/libeigen/eigen/-/archive/b9362fb8f76fbba805b56afbc0f5de0a279631b5/eigen-b9362fb8f76fbba805b56afbc0f5de0a279631b5.tar.gz",
    ],
)











