"""tests"""

load("//:defs.bzl", "py_pytest_test")

py_test(
    name = "whl_test",
    srcs = ["test_whl.py"],
    data = [
        "@futures_2_2_0_whl//file",
        "@futures_3_1_1_whl//file",
        "@google_cloud_language_whl//file",
        "@grpc_whl//file",
        "@mock_whl//file",
        "@pytest_flask_0_14_0_whl//file",
        "@ruamel_yaml_clib_0_2_0_whl//file",
    ],
    main = "test_whl.py",
    python_version = "PY3",
    deps = [
        "//src:whllib",
    ],
)
