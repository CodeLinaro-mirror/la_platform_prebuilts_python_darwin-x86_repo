package(default_visibility = ["//visibility:public"])

filegroup(
    name = "darwin-x86",
    srcs = glob(
        include = [
            "bin/*",
            "include/**",
            "lib/**",
            "share/**",
        ],
        exclude = [
            "**/*.pyc",
            "lib/python3.13/**/__pycache__/**",
        ],
    ),
)

filegroup(
    name = "darwin-x86-bundle",
    srcs = glob(
        include = ["lib/python3.13/**"],
        exclude = [
            "lib/python3.13/**/*.pyc",
            "lib/python3.13/**/__pycache__/**",
            "lib/python3.13/test/**",
            "lib/python3.13/unittest/**",
            "lib/python3.13/config/**",
            "lib/python3.13/distutils/**",
            "lib/python3.13/idlelib/**",
            "lib/python3.13/lib2to3/**",
            "lib/python3.13/plat-linux2/**",
            "lib/python3.13/bsddb/test/**",
            "lib/python3.13/ctypes/test/**",
            "lib/python3.13/email/test/**",
            "lib/python3.13/lib-tk/test/**",
            "lib/python3.13/sqlite3/test/**",
            "lib/python3.13/site-packages/setuptools/gui-64.exe",
            "lib/python3.13/site-packages/setuptools/gui.exe",
            "lib/python3.13/site-packages/setuptools/cli.exe",
            "lib/python3.13/site-packages/setuptools/cli-64.exe",
            "lib/python3.13/site-packages/setuptools/cli-32.exe",
            "lib/python3.13/site-packages/setuptools/gui-32.exe",
            "lib/python3.13/site-packages/pip/_vendor/distlib/w64.exe",
            "lib/python3.13/site-packages/pip/_vendor/distlib/t64.exe",
            "lib/python3.13/site-packages/pip/_vendor/distlib/t32.exe",
            "lib/python3.13/site-packages/pip/_vendor/distlib/w32.exe",
        ],
    ),
)
