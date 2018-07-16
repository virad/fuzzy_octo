cmake_minimum_required(VERSION 2.6)
add_executable(octo lagrange_prime.c test_program.c)
target_link_libraries( octo stdlib.so )
