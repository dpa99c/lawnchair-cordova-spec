Lawnchair Spec for Cordova/Phonegap
===================================

# Overview

This repo contains a Cordova/Phonegap project which runs the specs for [lawnchair](https://github.com/brianleroux/lawnchair) in Cordova/Phonegap environment.

This is especially intended to for testing the "cordova-native-sqlite" adapter, which provides an interface for lawnchair to a native SQLite DB on mobile platforms via the [cordova-sqlite-storage](https://github.com/litehelpers/Cordova-sqlite-storage) plugin, hence this adaptor can only be tested from within a Cordova/Phonegap native environment.

The other adapters are also tested, which is useful for testing adaptor support on various mobile platforms.

[![CLI screenshot](https://raw.githubusercontent.com/dpa99c/lawnchair-cordova-spec/master/screenshot/screen.png)](https://raw.githubusercontent.com/dpa99clawnchair-cordova-spec/master/screenshot/screen.png)

# Downloading

To download the example project, clone it using git:
```
$ git clone https://github.com/dpa99c/lawnchair-cordova-spec.git

```

# Running

To run the project, execute the `run` for your target platform using the CLI from the project root folder:
For example, to run on Android using Cordova:

    $ cordova run android

License
================

The MIT License

Copyright (c) 2015 Dave Alden/Working Edge Ltd.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.