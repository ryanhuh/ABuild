# ABuild
cocos2d-x-4.0 + cocosStuid 3.1
Build Requirements
------------------

* Mac OS X 10.7+, Xcode 8+
* or Ubuntu 14.04+, CMake 3.1+
* or Windows 7+, VS 2015
* Python 2.7.5+(NOT Python 3)
* NDK r16+ is required to build Android games
* Android Studio 3.0.0+ to build Android games(tested with 3.0.0)
* JRE or JDK 1.6+ is required for web publishing

Runtime Requirements
--------------------
  * iOS 8.0+ for iPhone / iPad games
  * Android 3.0.0+ for Android
  * OS X v10.9+ for Mac games
  * Windows 7+ for Win games

Environment Setup
--------------------

Should set up environment before starting a new game or running tests

```
$ cd cocos2d-x
$ ./setup.py
$ source FILE_TO_SAVE_SYSTEM_VARIABLE

```

Should invoke this script if using linux system

```
$ cd cocos2d-x
$ ./install-linux-deps.sh
```

Running Tests
--------------------

```
$ cd cocos2d-x
$ mkdir build
$ cd build
$ cocos run --proj-dir .. -p [mac|windows|android|linux|ios]
```

How to start a new game
-----------------------

    $ cd cocos2d-x
    $ ./setup.py
    $ source FILE_TO_SAVE_SYSTEM_VARIABLE
    $ cocos new MyGame -p com.your_company.mygame -l cpp -d NEW_PROJECTS_DIR
    $ cd NEW_PROJECTS_DIR/MyGame
    $ mkdir build
    $ cd build
    $ cocos run --proj-dir .. -p [mac|windows|android|linux|ios]

You can also create a Lua project with `-l lua`.
