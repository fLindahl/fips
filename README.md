fips
====

[![Build Status](https://travis-ci.org/floooh/fips.svg?branch=master)](https://travis-ci.org/floooh/fips)

fips is a highlevel build system wrapper written in Python for C/C++ projects.

Read the docs to get a better idea what this means:

http://floooh.github.io/fips/index.html

### Public Service Announcements

- **05-Feb-2015**: the NaCl SDK setup bug has been fixed by the NaCl team, so './fips setup nacl' should now work also with the latest Python 2.7.9

- **01-Feb-2015**: the code generation refactoring branch has been merged back into 
the master branch, code generation is now controlled with the new **fips_generate()**
cmake macro, see [Oryol engine](https://github.com/floooh/oryol) and 
[code generation doc page](http://floooh.github.io/fips/codegen.html) for details!

- **30-Jan-2015**: please note that the NaCl SDK setup script is currently broken with Python 2.7.9 (2.7.6 works), this is tracked in the following bug: https://code.google.com/p/chromium/issues/detail?id=452137  

### Progress

fips is currently heavily **work in progress**, everything may change or
break at any time.

I'm trying to put up progress videos from time to time:

- first progress video: https://www.youtube.com/watch?v=6F_AecDqRIY
- 2nd progress video: https://www.youtube.com/watch?v=W0MYjpR0G8c
- 3rd progress video: https://www.youtube.com/watch?v=3bQrYYaYU4w
- 4th progress video: https://vimeo.com/115050871
- using fips with Oryol 3D engine: https://www.youtube.com/watch?v=LaC4Sqatyts
- compiling and debugging in QtCreator and CLion IDEs: https://www.youtube.com/watch?v=Sp5TywYeNzE
- building a standalone Oryol app: https://www.youtube.com/watch?v=z8nwrGh2Zsc

