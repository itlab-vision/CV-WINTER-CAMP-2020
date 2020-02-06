# Материалы для практических занятий

## Профилирование и бенчмаркинг - практика

1. Разархивируйте архив `profiling_practice.zip`

1. Изучите лекцию `ParallelStudio.pptx` в архиве.

1. Соберите проект из архива и проведите эксперименты.

## Использование оптимизирующих компиляторов - практика

Для выполнения практики на собственном ноутбуке необходимо выполнить следующие действия:

1. Install Visual Studio 2019 Community Edition

1. Install latest CMake, either via following URL: https://github.com/Kitware/CMake/releases/download/v3.16.2/cmake-3.16.2-win64-x64.msi
or via official website cmake.org

1. Clone the following Git repository:
https://github.com/vshampor/llvm-project
so that the local path to the repository has no spaces (!)

1. If the local VS 2019 Community Edition main executable devenv.exe is not located at:
C:\Program Files (x86)\Microsoft Visual Studio\2019\Community\Common7\IDE\devenv.exe 
change the corresponding path in the llvm-project/deploy.bat file so that it points to the local VS 2019 Community Edition devenv.exe executable.

1. Run CMD, change the directory to the local llvm-project folder checked out during step 2, and run the following batch file:
deploy.bat
This operation will take a *lot* of time - make sure that the batch file run is completed.  

## Использование математических библиотек - практика

1. Разархивируйте архив `matlibs_practice.zip`

1. Соберите проекты из архива, изучите исходный код и сравните производительность различных оптимизаций кода.