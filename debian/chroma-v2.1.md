---
title: CHROMA-V2
section: 1
---

# NAME

**chroma-v2** - general purpose syntax highlighting program

# SYNOPSIS

| **chroma-v2** \[_options_\] _files_ ...

# DESCRIPTION

This manual page documents briefly the chroma-v2 command.

# OPTIONS

This program follow the usual GNU command-line syntax, with long
options starting with two dashes ('-').
A summary of options is included below.

--help

: Show context-sensitive help.

--list

: List lexers, styles and formatters.

--unbuffered

: Do not buffer output.

--trace

: Trace lexer states as they are traversed.

--check

: Do not format, check for tokenization errors instead.

--filename=_FILENAME_

: Filename to use for selecting a lexer when reading from stdin.

-l, --lexer=autodetect

: Lexer to use when formatting.

-s, --style=swapoff

: Style to use for formatting.

-f, --formatter=terminal

: Formatter to use.

--html

: Enable HTML mode (equivalent to '**--formatter html**').

--html-prefix=_PREFIX_

: HTML CSS class prefix.

--html-styles

: Output HTML CSS styles.

--html-only

: Output HTML fragment.

--html-inline-styles

: Output HTML with inline styles (no classes).

--html-tab-width=8

: Set the HTML tab width.

--html-lines

: Include line numbers in output.

--html-lines-table

: Split line numbers and code in a HTML table

--html-lines-style=_HTML-LINES-STYLE_

: Style for line numbers.

--html-highlight=_N[:M][,...]_

: Highlight these lines.

--html-highlight-style=_HTML-HIGHLIGHT-STYLE_

: Style used for highlighting lines.

--html-base-line=1

: Base line number.

--version

: Show application version.

# BUGS

See GitHub Issues: <https://github.com/alecthomas/chroma/issues>
