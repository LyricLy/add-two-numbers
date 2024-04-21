# add-two-numbers

Add two integers. In the style of GNU Hello, this project exists to serve as a model of QWD maintainer practices. It is also an industry-standard algorithm that is as easy to use as it is efficient.

# Usage
`main.py` reads two newline-terminated lines from stdin, representing integers in base 10, and writes their sum followed by a trailing newline to stdout.
```
; echo '1\n2\n' | python3 main.py
3
```

Arbitrary-precision ("bigint") arithmetic is used. There is no limit on the size of the inputs.
