# jink

[![Build Status](https://travis-ci.org/jink-lang/jink.svg?branch=master)](https://travis-ci.org/jink-lang/jink)
[![Discord](https://img.shields.io/discord/365599795886161941.svg)](https://discord.gg/cWzcQz2)

---

> Jink is a simplistic, JavaScript-like programming language built using Python.

I've built Jink to prove to myself that I can, not to make the most efficient, useful or mind-bending new language. I plan to support it for as long as I see fit, and contribution is very welcome. Thanks for checking it out!

## Progress Checklist

- [ ] Convert to compiler
- [ ] Module support
- [ ] File support
- [ ] I/O support
- [ ] Networking support

## Example

```jink
fun example_function(input) {
    return ++input
}

let output = example_function(1336)
print(output) // Prints 1337 to the console!
```

## Installation

Assuming you have Python 3.6 or newer, you can get started right away after cloning the project!

To launch the REPL:

```cmd
python jink.py
```

To execute your own files:

```cmd
python jink.py C:/path/to/file.jk
```

To execute the example files:

```cmd
python jink.py ./examples/01-hello_world.jk
```

### Building

#### Prerequisites

* Python 3.6+

#### Windows

1. Clone the project.
2. Run the included `build-executable.bat` file; this will install cx_Freeze and build the executable.

```cmd
cd build/exe.win32-3.x
jink.exe C:/path/to/your_file.jk
```

Optionally, you can move the contents of the /build/exe.win32-3.x folder to a folder you've added to your PATH. This will allow you to run Jink via your command line.

## Contributing

I will set up a contribution guide when I can. In the meantime, feel free to provide feedback in any way you see fit. This project is still fairly new, after all.

## Acknowledgements

* Enormous thanks to [king1600](https://github.com/king1600) for helping me to better understand interpreter and compiler design and providing me the resources and support I needed to carry out this project.

* This project also would not have been possible without the incredible resources on PL implementation at [Mihai Bazon's blog](http://lisperator.net).

## License

This project is distributed under the MIT License - see the [license file](LICENSE) for details.

Copyright © 2018 Jacob Buzalski
