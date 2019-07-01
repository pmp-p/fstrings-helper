helper to convert f-strings before sending code to micropython or to the bytecode compiler mpy-cross

usage:  python3.7 -mfstrings_helper filename


note: requires the tokenize_rt module from https://github.com/asottile/tokenize-rt


many thanks to original author since micropython is unlikely to support natively f-strings as it would increase its core size.

NEW! future-fstrings[rewrite] now provides a command line tool for code conversion
    check it there https://github.com/asottile/future-fstrings#transform-source-for-micropython



watch for:
    https://docs.python.org/3.8/whatsnew/3.8.html#f-strings-now-support-for-quick-and-easy-debugging
    and maybe it's future support https://github.com/asottile/future-fstrings/issues/40
