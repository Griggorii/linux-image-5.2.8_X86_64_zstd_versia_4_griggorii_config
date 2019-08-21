# linux-image-5.2.8_X86_64_zstd_versia_4_griggorii_config_kernel
linux-image-5.2.8_X86_64_zstd_versia_4_griggorii_config_kernel

Добавленна поддержка UDF NLS так как третий конфиг не был проставлен и на нём не читались dvd болванки

Скачать ядро deb пакетами https://drive.google.com/open?id=1zo2XaA-AnvcjAkcLK2AiZIvPxSVCUq43

Переименовываем Griggorii_16.04_или_19.04_compiler_.config в папке kernel в .config и из терминала выполняем

make -j4 bindeb-pkg

-j4 это у меня столько ядер у вас может быть меньше или больше если больше то ещё быстрее закончится компиляция.
