<h1>
  <img src="assets/images/icon.png" alt="ByteShell icon" width="32" height="32" style="vertical-align: middle; margin-right: 8px;" />
  ByteShell
</h1>


ByteShell is a UNIX-like command-line shell written in C. It's a simple shell used to execute built-in Linux commands.


### Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Resources](#resources)
- [Contributing](#contributing)


### Installation


**Requirements** :

- **Language**: C  
- **Compiler**: `gcc` (or any POSIX-compliant C compiler)  
- **Environment**: UNIX-like system (Linux, macOS, WSL, etc.)

```bash
# Use the provided compilation command:
gcc *.c

# This compiles all C source files and produces an executable (by default `a.out`).
# After a successful compilation, run:
./a.out
```

If everything is set up correctly, you will see the ByteShell prompt:

```text
>
```

### Usage

<br>

**Builtins implemented:**

- **`echo`**: Print its arguments to standard output.
- **`cd`**: Change the current working directory.
- **`pwd`**: Print the current working directory.
- **`exit`**: Exit the shell.

**Examples:**


```text
> echo hello world
hello world

> cd /

> pwd
/Users/Praveen/documents/projects-new/byte-shell

> exit
```


### Resources

- [Write a Shell in C](https://brennan.io/2015/01/16/write-a-shell-in-c/)
- [Linux Commands Man Pages](https://linuxcommand.org/lc3_man_page_index.php)

### Contributing

Contributions are welcome! To propose changes:

1. Fork the repository and create a feature branch
2. Make your changes
3. Open a Pull Request with a clear description and examples
