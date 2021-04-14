# ImPlot Core
implot_sources = [
  'implot.cpp',
  'implot_items.cpp',
]

implot_deps = [
  libimgui_core_dep,
]

libimplot = static_library('implot',
  files(implot_sources),
  dependencies : implot_deps,
  install: true,
)

libimplot_dep = declare_dependency(
  link_with : libimplot,
  include_directories : include_directories('.'),
)

