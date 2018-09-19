package(default_visibility = ["//visibility:public"])

load(
    "@io_tweag_rules_haskell//haskell:haskell.bzl",
    "haskell_library",
)

haskell_library(
    name = "pipeline-tools",
    srcs = glob(["src/**/*.hs"]),
    src_strip_prefix = "src",
    deps =
        [
            "//hackage:aeson",
            "//hackage:amazonka",
            "//hackage:amazonka-core",
            "//hackage:amazonka-s3",
            "//hackage:amazonka-s3-streaming",
            "//hackage:base",
            "//hackage:basic-prelude",
            "//hackage:binary",
            "//hackage:binary-orphans",
            "//hackage:bytestring",
            "//hackage:clock",
            "//hackage:conduit",
            "//hackage:conduit-extra",
            "//hackage:containers",
	    "//hackage:contravariant",
            "//hackage:data-default",
            "//hackage:deepseq",
            "//hackage:directory",
            "//hackage:distributed-closure",
            "//hackage:exceptions",
            "//hackage:filepath",
            "//hackage:formatting",
            "//hackage:hashable",
            "//hackage:katip",
            "//hackage:lens",
            "//hackage:monad-control",
            "//hackage:mtl",
            "//hackage:optparse-applicative",
            "//hackage:resourcet",
            "//hackage:streaming",
            "//hackage:streaming-bytestring",
            "//hackage:streaming-conduit",
            "//hackage:template-haskell",
            "//hackage:temporary",
            "//hackage:text",
            "//hackage:unliftio-core",
            "//hackage:unordered-containers",
            "//hackage:url",
            "//hackage:vinyl",
            "//hackage:yaml",
        ],
)
