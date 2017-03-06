include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'mstch',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', 'mstch/**/*.hpp'),
  ]),
  headers = subdir_glob([
    ('src', '**/*.hpp'),
  ]),
  srcs = glob([
    'src/**/*.cpp'
  ]),
  compiler_flags = [
    '-std=c++14',
  ],
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
