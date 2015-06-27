# Bit Slicer
![Bit Slicer icon](https://dl.dropbox.com/u/10108199/bit_slicer/web_icon.png)

[Download Bit Slicer 1.7.5](https://bitbucket.org/zorgiepoo/bit-slicer/downloads/Bit%20Slicer%201.7.5.zip)

## Introduction
Bit Slicer is a universal game trainer for OS X, written using Cocoa and Mach kernel APIs.

It allows you to cheat in video games by searching and modifying values such as your score, lives, ammunition, and much more.

*Disclaimer: Use this software at your own risk. I'm not responsible for any damage that could occur.*

## Features
* Memory Scanner
	* Search & narrow down values of several types: integers, floating-points, strings, byte arrays, and pointers
	* Add, delete, and modify variables with ease
	* Freeze variable's values
	* Store a process' entire virtual memory space and search for values based on incremental changes
	* Manipulate pointers by dereferencing variable addresses
* Memory Inspection
	* View and edit memory live in a hex editor style window
	* Dump memory to files on disk for manual inspection
	* Modify memory protection attributes
* Debugger
	* View live disassembly of instructions
	* Modify instruction's bytes directly, or by assembling instructions (including nopping)
	* Set breakpoints, resume from them when they're hit, view backtraces, manipulate thread registers, and step into/out/over instructions
	* Inject x86 code on the fly
	* Watch for what instructions access a variable in a document
* Save slice documents so that you can send cheats to your friends
* Write Scripts to automate tasks that involve using virtual memory and debugger methods
* Pause and un-pause current process
* Undo & Redo many kinds of changes, including searches
* Evaluate mathematical expressions automatically (eg: in a flash game, search for 58 * 8)
* Run as a normal user, not as the superuser (root)!
* Enjoy OS level features such as auto-saving, document versioning, window restoration, notification center, app nap, etc.


## System Requirements
* **Bit Slicer 1.7.5**: OS X 10.8 or newer
* [Bit Slicer 1.6.2](https://bitbucket.org/zorgiepoo/bit-slicer/downloads/Bit%20Slicer%201.6.2.zip): OS X 10.6.8, a 64-bit intel Mac
* [Bit Slicer 1.5.2](https://bitbucket.org/zorgiepoo/bit-slicer/downloads/Bit%20Slicer%201.5.2.zip): OS X 10.6.8

## Support
* Check the [wiki](https://github.com/zorgiepoo/Bit-Slicer/wiki/) for how to use Bit Slicer
* Visit the [forums](http://portingteam.com/forum/157-bit-slicer/) for discussion and current development
* Visit the [chat room](http://webchat.freenode.net/?channels=bitslicer) for support or development (#bitslicer on irc.freenode.net). Note I am not available 24/7.
* Send an email to zorgiepoo (at) gmail (dot) com

## Contributing
* Improve the current [wiki](https://github.com/zorgiepoo/Bit-Slicer/wiki/) by fixing errors or by adding content
* Report bugs or request features on the [issue tracker](https://github.com/zorgiepoo/Bit-Slicer/issues)
* Help [translate](https://github.com/zorgiepoo/Bit-Slicer/wiki/Localization) Bit Slicer into a different language
* Help [design improved artwork](https://github.com/zorgiepoo/Bit-Slicer/issues/18)
* Learn how to build and contribute to the [source code](https://github.com/zorgiepoo/Bit-Slicer/wiki/Source-Code)

Please read this project's [Code Of Conduct](https://github.com/zorgiepoo/Bit-Slicer/blob/master/CODE_OF_CONDUCT.md) residing in the root level of the project.
