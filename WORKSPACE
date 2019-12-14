# -*- mode: python -*-
# vi: set ft=python :

workspace(name = "inekf")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Eigen
http_archive(
    name = "eigen",
    build_file = "//:eigen.BUILD",
    sha256 = "94878cbfa27b0d0fbc64c00d4aafa137f678d5315ae62ba4aecddbd4269ae75f",
    url = "https://bitbucket.org/eigen/eigen/get/3.3.3.tar.g://bitbucket.org/eigen/eigen/get/3.3.3.tar.gz",
    strip_prefix = "eigen-eigen-67e894c6cd8f",
)
