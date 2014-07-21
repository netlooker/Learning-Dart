Learning-Dart
=============

I've created this repository only for learning purposes. I'm interested in the new technology provided by Google Geeks and I want to explore it.

### Installation issues on Ubuntu 13 and Mint 15
On Ubuntu 13.04, Linux Mint 15, Dartium issues the following error on startup and terminates:
> Dartium stdout: /home/user/Applications/dart/chromium/chrome: error while loading shared libraries: libudev.so.0: cannot open shared object file: No such file or directory.

Ther is a temporary workaround. Just put this in your bash and run.
```
sudo ln -s /lib/x86_64-linux-gnu/libudev.so.1 /lib/x86_64-linux-gnu/libudev.so.0
```

After applaying this I was able to run Dart projects on my localhost.

### First steps in a new language
1. I'm following instruction from this tutorial https://www.dartlang.org/codelabs/darrrt/
2. My notes and impressions about Dart
  - Dart looks similar to JAVA language
  - Dart uses CSS selcetors to get elements form the DOM
  - dart:core - main library which is automatically imported into every Dart app
  - **dart:html** - library which contains the classes for all DOM element types, in addition to functions for accessing the DOM
  - **dart:convert, dart:async, dart:math** - another useful libraries
  - you can import only stuff that you realy need in your project using the **"show"** keyword
3. You can find more details about Dart libraries API here https://api.dartlang.org
4. OOP rules in Dart
  - **static** defines a class-level field
  - **final** variables cannot change
  - private variables start with **underscore (_)**; Dart has **no private keyword**
  - constructors have the same name as the class
  - the parameters enclosed in curly brackets ({ and }) are optional
  - getters are special methods that provide read access to an object’s properties
  - **List** is a generic type. List can contain any kind of object. If you intend for a list to contain only strings, you can declare it as List<String>
  - using underscore (_) as a parameter name indicates that the parameter is ignored.



