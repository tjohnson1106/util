scala_library(
    compiler_option_sets = ["fatal_warnings"],
    provides = scala_artifact(
        org = "com.twitter",
        name = "util-reflect",
        repo = artifactory,
    ),
    dependencies = [
        "3rdparty/jvm/cglib",
        "util/util-core:util-core-util",
    ],
    exports = [
        "3rdparty/jvm/cglib",
    ],
)
