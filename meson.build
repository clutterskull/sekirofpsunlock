project('sekirofpsunlock', 'c', default_options : ['c_std=c17'], version : '0.3.0')

c_args = ['-Wall', '-Wextra', '-Wpedantic']

executable('sekirofpsunlock',
           'src/main.c',
           'src/common.c',
           'src/signals.c',
           'src/sekiro.c',
           'src/fps.c',
           'src/resolution.c',
           'src/extras.c',
           c_args : c_args)
