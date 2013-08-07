NAME
    dgrep -- David's badass grep with fancy colors and cool features

SYNOPSIS
    dgrep [-ainpw] [expression] [-v] [expression] [file ...]
    dgrep [-h | -V]

DESCRIPRION
    -a, --all			print all text with matches inline
    -h, --help			print this help
    -i, --insensitive		match case insensitive
    -n, --number		prepend line number
    -p, --paragraph		match in paragraph context
    -V, --version		print version information and exit 
    -v, --invert-match		selected lines do not match specified pattern
    -w, --word			match whole word

    Matched expressions will be highlighted to illustrate against which criteria they were matched.
    Whole word matches will be highlighted in magenta and supercede other highlighted colors. Exact
    expression matches will be highlighted in red and case insensitive matches will be  highlighted
    in yellow.

Report bugs to <david@soinkleined.com>
