plank_default_theme_dir = join_paths(get_option('datadir'), 'plank/themes')

flavours = []
foreach flavour: ['default', 'dark']
  if not get_option(flavour)
    message('skip flavour ' + flavour)
    continue
  endif
  flavours += flavour
endforeach

subdir('src')
