add_executable(
    main.exe
    main.c
    src/hello.c
    src/bojour.c
)
target_include_directories(
    main.exe
    PUBLIC inc
)