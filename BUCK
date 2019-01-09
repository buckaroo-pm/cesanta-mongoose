load('//:buckaroo_macros.bzl', 'buckaroo_deps')

cxx_library(
  name = 'mongoose',
  header_namespace = '',
  exported_headers = [
    'mongoose.h',
  ],
  srcs = [
    'mongoose.c',
  ],
  licenses = [
    'LICENSE',
  ],
  platform_deps = [
    ('linux.*', buckaroo_deps()),
  ],
  visibility = [
    'PUBLIC'
  ],
)
