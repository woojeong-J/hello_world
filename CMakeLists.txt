add_executable(
    main.exe
    main.c
    src/hello.c
)
target_include_directories(
    main.exe
    PUBLIC inc
)