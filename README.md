# JHack
### コンピュータを制御するためのC++ライブラリ


このライブラリは、C++とWinAPIの練習と、ゲームハッキングの初挑戦のために作りました。

魅力的な紹介文の裏側には、WinAPIのラッパーである非常にシンプルなC++17ライブラリがあります。
このライブラリの目的は、プロセスに簡単にアクセスし、変更することです。
その上で、ゲームハックのプログラミングに役立つような便利な機能を作りたい !

## 特徴
Here is a list of the current features:
- a `start()` function that print "Hello World"! (**amazing**)
- a `getProcessHandleByName()` function to retrieve a Process Handle.


## Compilation
Just run the CMakeLists.txt file with the command `cmake`. You may want to build the project in a separate directory, for example `build/`. Both `build.sh` and `build.ps1` scripts can do that for you.

In order to test the program, you first need to enable the tests in the cmake configuration (`cmake -DENABLE_TESTS=ON`, done by the build scripts). Then you just need to run `ctest` in your build directory.
