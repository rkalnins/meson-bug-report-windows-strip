project('dcmu', 'c', 'cython', default_options : ['buildtype=release', 'c_std=c99'])

cython = find_program('cython')

cmake = import('cmake')
py = import('python').find_installation()
py_dep = py.dependency()

# this line resolves
# fatal error LNK1112: module machine type 'x86' conflicts with target machine type 'x64'
add_global_arguments('-DMS_WIN64', language: ['c'])

subdir('wintest')