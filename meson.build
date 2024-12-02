project('ght', 'c',
    default_options: [
        'werror=true',
        'warning_level=3',
        'c_std=c23'
    ]
)

add_global_arguments(
    '-D_GHT_THREAD_SAFE',
    language: 'c'
)

subdir('ght/')
subdir('example/')
