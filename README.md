# CLI template for C/C++

This is template app for CLI test.  
You can make console application by editing files under src directory.
As default, app.cpp has `main` function. You can start to develop from here.

## How to get input parameters
Same as ususal C++ application, `main` function takes following parameters.
app.py has a function `main`

- `int argc`: The number of parameters. (including program name.)
- `char *argv[]`: The array of char pointer.

## How to output result
You can use `cout`, `printf`, etc.

``` c++
  cout << argv[0] << endl
```

## How to compile
To compile, we are using [clang](http://clang.llvm.org/) c++ command.

If you want to change compile option or etc, please edit [codecheck.yml](codecheck.yml) `build` section.  
(If you change output filename, you have to change env/APP_COMMAND section too.)

You can build pure C application by switching compiler command from `c++` to `clang`.
