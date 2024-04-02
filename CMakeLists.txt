cmake_minimum_required(VERSION 3.0)
project(MeuProjeto VERSION 1.0)

# Adiciona o executável
add_executable(hello hello.cpp)


# Especifica onde o executável será instalado
install(TARGETS hello
        DESTINATION bin)

