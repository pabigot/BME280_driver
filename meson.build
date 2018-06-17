project('BME280_driver', 'c',
        version: '3.3.6',
        license: 'BSD-3-Clause')

bme280_dep = declare_dependency(link_with: static_library('bme280', 'bme280.c',
                                                          pic: false),
                                include_directories: include_directories('.'))
