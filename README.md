# TermiC

Inspired by Termithron made by [idkDwij](https://github.com/IdkDwij/Termithon) on GitHub. Its written in C for now. (_I will learn C++ later on_)

## Installation

[Visual Studio Code](https://code.visualstudio.com/) (_Make sure to install the C/C++ Extensions from the Marketplace to compile! AND the GNU compiler_)

[CodeBlocks](https://www.codeblocks.org/) (Nothing required to compile)

![Installation](https://code.visualstudio.com/assets/docs/languages/cpp/cpp-extension.png)
![Alt](https://www.codeblocks.org/docs/cb_splash.png)

## The intial code...

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    printf("_________________________\n");
    printf("        TERMINAL\n");
    printf("_________________________\n");
    printf("\n");
    char dev[] = "joalricha869";
    printf("Made in C by %s\n", dev);
    return 0;
}
```

# Commands list

```c
/*
    You can enter the following commands:
    write  >>> To write to a file
    read   >>> To read from a file
    append >>> To append a file
    remove >>> To remove a file
    rename >>> To rename a file
    clr    >>> To clear the screen
    dt     >>> To show date and time
    stscr  >>> To show start screen
    edit   >>> To edit a file
    cdir   >>> To see the directory(location) and files
    copy   >>> To copy one file to new file or append to a existing file
    cknow  >>> To know how many time(s) a character repeated in file
    lknow  >>> To know how line(s) are there in a file
    gcd    >>> To perform GCD of numbers
    lcm    >>> To perform LCM of numbers
    tconv  >>> To convert temperatures
    exit   >>> To exit
    green  >>> To change color to green (WINDOWS ONLY)
    cmd    >>> To open up Windows Command Prompt
    bash   >>> To open up Linux BASH Prompt
*/
```

## What I am planning this terminal to look like...
![Terminal](https://upload.wikimedia.org/wikipedia/commons/7/78/Appleterminal2.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU 3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
