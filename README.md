# archnews
Python utility for displaying [Arch news feed](https://www.archlinux.org/feeds/news/) in console.

I was looking for an utility that would quickly show the [Arch Linux](https://www.archlinux.org/) news feed
in command line before upgrading my system. Unfortunately I did not find any program that would suit my needs.
So I wrote my own and I took it also as a practice in Python programming.

Features:
 - It is written in pure Python 3, no extra dependencies are needed.
 - It wraps feed description to improve readability and tries to interpret HTML as nicely as possible.
 - It uses colors. (Can be turned off.)
 - Time is formatted according locale.
 - Many command line options! (See `--help`.)
