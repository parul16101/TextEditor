# Kilo Text Editor

Kilo is a minimalist text editor crafted in less than 1,000 lines of code, as counted by cloc. Designed by Salvatore Sanfilippo, also known as Antirez, it embodies simplicity, efficiency, and ease of comprehension.

## Usage

To utilize Kilo, simply invoke it with a filename as follows: kilo

## Keys:

CTRL-S: Save <br />
CTRL-Q: Quit <br />
CTRL-F: Find string in file (ESC to exit search, arrows to navigate)

## Features

Kilo is built without dependency on any external library, including curses. It leverages standard VT100 (and similar terminals) escape sequences for its functionality. Despite being in its alpha stage, Kilo demonstrates robustness and efficiency.

Development Initially conceived within just a few hours, Kilo amalgamates code from Antirez's previous projects, load81 and linenoise. It serves as an excellent foundation for developing more sophisticated text editors or command-line interfaces beyond the typical REPL style CLI.

