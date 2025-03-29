project('rock-bot', 'c',
  version : '0.1',
  default_options : ['warning_level=3'])

subdir('src')

exe = executable('rock-bot', sources,
  install : true)

test('basic', exe)
