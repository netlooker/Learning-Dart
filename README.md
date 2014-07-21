Learning-Dart
=============

I've created this repository only for learning purposes. I'm interested in the new technology provided by Google Geeks and I want to explore it.

# Installation issues on Ubuntu 13 and Mint 15

On Ubuntu 13.04, Linux Mint 15, Dartium issues the following error on startup and terminates:

> Dartium stdout: /home/user/Applications/dart/chromium/chrome: error while loading shared libraries: libudev.so.0: cannot open shared object file: No such file or directory.

Ther is a temporary workaround. Just put this in your bash and run.
```
sudo ln -s /lib/x86_64-linux-gnu/libudev.so.1 /lib/x86_64-linux-gnu/libudev.so.0
```

After applaying this I was able to run Dart projects on my localhost.
