package(default_visibility = ["//visibility:public"])

filegroup(
    name = "gcc",
    srcs = [
        "bin/arc-linux-gcc",
    ],
)

filegroup(
    name = "ar",
    srcs = [
        "bin/arc-linux-ar",
    ],
)

filegroup(
    name = "ld",
    srcs = [
        "bin/arc-linux-ld",
    ],
)

filegroup(
    name = "nm",
    srcs = [
        "bin/arc-linux-nm",
    ],
)

filegroup(
    name = "objcopy",
    srcs = [
        "bin/arc-linux-objcopy",
    ],
)

filegroup(
    name = "objdump",
    srcs = [
        "bin/arc-linux-objdump",
    ],
)

filegroup(
    name = "strip",
    srcs = [
        "bin/arc-linux-strip",
    ],
)

filegroup(
    name = "as",
    srcs = [
        "bin/arc-linux-as",
    ],
)

filegroup(
    name = "compiler_pieces",
    srcs = glob([
        "arc-snps-linux-uclibc/**",
        "libexec/**",
        "lib/gcc/arc-snps-linux-uclibc/**",
        "include/**",
    ]),
)

filegroup(
    name = "compiler_components",
    srcs = [
        ":ar",
        ":as",
        ":gcc",
        ":ld",
        ":nm",
        ":objcopy",
        ":objdump",
        ":strip",
    ],
)
