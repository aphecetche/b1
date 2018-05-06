MS_GSL_BUILD = """
cc_library(
    name = "ms_gsl",
    hdrs = glob(["include/gsl/*.h"]),
    includes = ["include"],
    visibility=["//visibility:public"],
)
""" 

new_http_archive(
    name = "ms_gsl",
    urls= ["https://github.com/Microsoft/GSL/archive/v1.0.0.tar.gz"],
    sha256 = "9694b04cd78e5b1a769868f19fdd9eea2002de3d4c3a81a1b769209364543c36",
    strip_prefix = "GSL-1.0.0",
    build_file_content = MS_GSL_BUILD,
)
