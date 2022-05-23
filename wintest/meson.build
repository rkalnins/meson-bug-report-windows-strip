py.extension_module(
    'foo',
    'foo.pyx',
    dependencies : [py_dep],
    install : true,
    subdir : 'wintest'
)

python_sources = [
    '__init__.py',
    'test.py',
]

py.install_sources(python_sources,
    pure : true,
    subdir : 'wintest'
)