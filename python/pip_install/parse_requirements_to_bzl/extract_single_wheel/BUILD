filegroup(
    name = "distribution",
    srcs = glob(
        ["*"],
        exclude = ["*_test.py"],
    ),
    visibility = ["//python/pip_install:__subpackages__"],
)

filegroup(
    name = "py_srcs",
    srcs = glob(
        include = ["**/*.py"],
        exclude = ["**/*_test.py"],
    ),
    visibility = ["//python/pip_install:__subpackages__"],
)
