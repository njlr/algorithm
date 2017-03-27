include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'algorithm',
  header_only = True, 
  header_namespace = 'boost/algorithm',
  exported_headers = subdir_glob([
    ('include/boost/algorithm', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
