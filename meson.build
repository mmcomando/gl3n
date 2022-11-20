project('gl3n', 'd')

src = files(
  # 'gl3n/aabb.d',
  # 'gl3n/frustum.d',
  # 'gl3n/interpolate.d',
  'gl3n/linalg.d',
  'gl3n/math.d',
  # 'gl3n/plane.d',
  # 'gl3n/util.d',
)

lib = library('gl3n', src,
  include_directories : ['.']
)

gl3n_dep = declare_dependency(
  include_directories : ['.'],
  link_with : lib,
)

meson.override_dependency('gl3n', gl3n_dep)