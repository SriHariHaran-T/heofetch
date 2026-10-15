# heofetch

A lightweight Bash-based system information tool for Linux, built as my first shell scripting project.

HeoFetch displays useful information about your system directly in the terminal, with custom colours and a few fun command-line options.

## Features

- Displays operating system information
- Shows kernel version and machine architecture
- Displays the current username
- Shows system uptime
- Displays used and total RAM
- Custom terminal colours
- Help and version options
- Instagram link option
- Handles invalid command-line arguments

## Usage

Run HeoFetch from your terminal:

```bash
heofetch
```

### Available options

| Option | Description |
| --- | --- |
| `--help` | Display help information |
| `--version` | Display the current version |
| `--follow` | Display my Instagram link |

Unsupported options display an error message.

## Requirements

- Linux
- Bash
- Standard Linux utilities, including `uname`, `uptime`, `free`, and `awk`

## Installation

Clone this repository:

```bash
git clone 
cd heofetch
```

Make the script executable:

```bash
chmod +x heofetch
```

Run it:

```bash
./heofetch
```

To run HeoFetch from any directory, place the executable in a directory included in your `PATH`, such as `~/.local/bin`.

## Why I built this

HeoFetch started as a small project to practise Bash scripting on Arch Linux. While building it, I explored variables, command substitution, functions, conditionals, ANSI colours, command-line arguments, pipes, `awk`, and exit codes.

This project is a work in progress, and I plan to improve it as I continue learning Linux and shell scripting.

## Author

**Hari | heodoestech**

- Instagram: [@heodoestech](https://www.instagram.com/heodoestech/)

## License

No license has been selected yet. Reuse and redistribution permissions will be clarified when a license is added.
