# Simple Shell, Checks

This repo centralizes all checks made by VCFR-0920 for the simple_shell project.

This repo currently contains 60 checks, including **47** *original* scripts from **10** authors from VCFR-0920.


## Configuration

Open the file `config` and update the variable `SHELL` with your shell.

## Run

Usage `./check_simple_shell.bash`

## Misc

### Note for check allowed function

Check_allowed_function : check if there is not allowed function used with the command : /bin/ls
Check_allowed_function_advanced : check if there is not allowed function used with the command : env, ls -la, setenv, unset.

Be carefully, this test only work with gcc version 4.8.4, if you compiled with an other version, it's possible that ltrace do not work correctly.
