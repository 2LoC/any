project('any', 'cpp',
        license : 'boost',
        meson_version : '>0.42.0',
        default_options : ['cpp_std=c++11'])

# Dependency
any = declare_dependency(include_directories : [ '.' ])
install_headers('any.hpp', install_dir : 'any')

test_any = executable('test_any', [ 'test_any.cpp' ],
                      cpp_args : [ '-Wall', '-Wextra' ]
                      )

test('test any', test_any)
