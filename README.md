helper to convert f-strings before sending code to micropython or to the bytecode compiler mpy-cross

usage:  python3.7 -mfstrings_helper filename


note: requires the tokenize_rt module from https://github.com/asottile/tokenize-rt


many thanks to original author since micropython is unlikely to support natively f-strings as it would increase its core size.
