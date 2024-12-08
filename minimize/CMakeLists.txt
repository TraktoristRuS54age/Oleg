cmake_minimum_required(VERSION 3.10)

#имя проекта
project(minimize)

#стандарт с++
set(CMAKE_CXX_STANDARD 11)

#добавление исходных файлов
set(SOURCE_FILES
	
	minimize.cpp
	minimize.h
)

#добавление исполняемого файла
add_executable(Minimize ${SOURCE_FILES})
