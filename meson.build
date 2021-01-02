project('range-v3', 'cpp', version: '0.11.0',
        license: 'Boost, libc++, Stepanov and McJones "Elements of Programming", SGI STL',
        meson_version: ">=0.54.0")

range_inc = include_directories('include')

range_dep = declare_dependency(
  include_directories : range_inc
)

meson.override_dependency('range-v3', range_dep)
