cmake_minimum_required(VERSION 3.5)

project(tmau1)

# Установка стандарта C++ (если требуется)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Добавление исполняемого файла с исходным именем
add_executable(Tmau_Laba1 tmau1.cpp)

# Настройка флагов компиляции
target_compile_options(Tmau_Laba1 PRIVATE -Wall)
