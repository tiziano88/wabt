cc_library(
    name = "wabt",
    srcs = glob([
        "src/*.cc",
        "src/interp/*.cc",
        "src/prebuilt/*.cc",
    ],
    exclude=[
        "src/test-*",
        "src/wast-lexer.cc",
    ]),
    hdrs = glob([
        "config.h",
        "src/*.h",
        "src/interp/*.h",
        "src/prebuilt/*.h",
    ]),
    textual_hdrs = [
        "src/opcode.def",
        "src/feature.def",
        "src/token.def",
        "src/prebuilt/wasm2c.include.h",
        "src/prebuilt/wasm2c.include.c",
        "src/range.h",
    ],
)
