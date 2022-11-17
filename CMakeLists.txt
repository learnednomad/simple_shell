cmake_minimum_required(VERSION 3.23)
project(simple_shell_master C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(simple_shell_master
        aux_error1.c
        aux_error2.c
        aux_help.c
        aux_help2.c
        aux_lists.c
        aux_lists2.c
        aux_mem.c
        aux_stdlib.c
        aux_str.c
        aux_str2.c
        aux_str3.c
        cd.c
        cd_shell.c
        check_syntax_error.c
        cmd_exec.c
        env1.c
        env2.c
        exec_line.c
        exit_shell.c
        get_builtin.c
        get_error.c
        get_help.c
        get_line.c
        get_sigint.c
        main.c
        main.h
        read_line.c
        rep_var.c
        shell_loop.c
        split.c)
