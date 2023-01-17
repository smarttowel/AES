project('aes', 'cpp',
    license : 'MIT',
    default_options: ['cpp_std=c++17',
                      'warning_level=2'])

aes_lib = static_library('aes',
                         'src/AES.cpp')

aes_dep = declare_dependency(link_with: aes_lib,
                             include_directories: include_directories('src'))
