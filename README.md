# Simple Shell, Checks

This repo centralizes all checks made by VCFR-0920 for the simple_shell project.

There are 60 checks available, including **47** *original* scripts from **10** authors from VCFR-0920.


## Installation & configuration

Clone this repo on the same machine that runs your shell.
Open the `config` file and update the `SHELL` variable with the path to your shell (both absolute & relative paths work).


## Usage

* Step 1: Run `$ ./check_simple_shell.bash`
* Step 2: Cry
* Step 3: Fix bugs
* Step 4: Repeat


## Notes

### check_allowed_function

* `check_allowed_function`: looks for forbidden functions while running the command : /bin/ls
* `check_allowed_function_advanced`: looks for forbidden functions while running the commands : env, ls -la, setenv, unsetenv.

*Note:* this test only work if your shell was compiled with `gcc-4.8.4`. Other versions of gcc have been known to cause `ltrace` to behave unpredictably. Use at your own risk and don't take the results for granted!
