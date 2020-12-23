# Calculator

## Thanks to

https://blog.csdn.net/luoluozlb/article/details/78793252 (0.1.0)

## Description:

This is a calculator that supports functions(e.g. sin(30))and unit conversion(e.g. 1(g/cm^3)/(kg/m^3)).

## OS

Mainly for windows,I don't know whether it can run on linus,Mac,etc.

I'm trying to make it more portable.

## About file system

{
    lang:{//language package
        en-uk.txt//English
        zh-CN.txt//Chinese
    },
    save:{//saving
        AboutSave.txt
        setting.data//if you have saved the setting
    },
    src:{//main code
        main.cpp
        |-calcintergrate.h&.cpp
          |-calcexpress.h&.cpp
            |-calchelper.h&.cpp
            |-calcdim.h&.cpp
            |-calcset.h&.cpp
              |-calcreadfile.h&.cpp
        // |- means #include
    },
    KNOWNBUGS.md,
    LICENSE,
    README.md,
}

## Feature

### In Code

- Pure C++

- Using C++11 standard

- Using try-catch-throw

- Using long double

- Using mt19937

### In Programe

- Press Enter three times and it will clear the window

- Colourful words

## Language

- en-uk

- zh-CN

## Useful Commands(You can try)

- /random,/dice

- /help

- /exit

- /debug,/disdebug

- /information

- /example

- /save

- /mr,/m+,/m-,/ms

- /color
