# Overview

`bound` is a command line tool with behavior similar to C++'s [std::lower_bound](https://en.cppreference.com/w/cpp/algorithm/lower_bound): given a string and a file (or stdin), `bound` returns the first line whose value is greater than or equal to the given string.

## Delimited lines of input

If the `-f i` option is specified, `bound` returns the first line whose i-th field is greater than or equal to the given string.

Fields are delimited by the space character (' ') by default, but can the delimiter can be specified with the `-d` option.

## Line number

The line number --- instead of the line itself --- can be returned with the `-i` option.

# Author

Thomas Fischer

# License

[GNU AFFERO GENERAL PUBLIC LICENSE.](https://www.gnu.org/licenses/agpl-3.0.txt)
