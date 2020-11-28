# Simple Shell, Checks

This repo centralizes all checks made by VCFR-0920 for the simple_shell project.

Currently, 60 checks are available, including **47** *original* scripts from **10** authors from VCFR-0920.


## Installation & configuration

Clone this repo on the same machine that runs your shell.
Open the `config` file and update the `SHELL` variable with the path to your shell (both absolute & relative paths work).


## Usage

* Step 1: Run `$ ./check_simple_shell.bash`
* Step 2: Cry
* Step 3: Fix bugs
* Step 4: Repeat


## Misc

### Note for check allowed function

Check_allowed_function : check if there is not allowed function used with the command : /bin/ls
Check_allowed_function_advanced : check if there is not allowed function used with the command : env, ls -la, setenv, unset.

Be carefully, this test only work with gcc version 4.8.4, if you compiled with an other version, it's possible that ltrace do not work correctly.
