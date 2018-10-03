```sh
$ ./bin/test -gen 5 5 ran -e 0.1

Result | Count | Rank
-------+-------+-------
   182 |     0 |    22
   370 |     0 |    18
   104 |     0 |    23
   423 |     0 |    14
    14 |     0 |    25
   393 |     0 |    17
   439 |     0 |    12
   401 |     0 |    16
   289 |     0 |    20
   217 |     0 |    21
   412 |     0 |    15
   344 |     0 |    19
   615 |     0 |     9
    20 |     0 |    24
   428 |     2 |    13
   606 |     5 |    10
   641 |     5 |     8
   500 |     7 |    11
   678 |     8 |     7
   685 |    53 |     6
   723 |    53 |     5
   885 |   110 |     3
   869 |   176 |     4
   921 |   260 |     2
   949 |   321 |     1
=======================

Trials:
    1000

Iterations per trial:
    min  20
    max  56
    mean 26


$ ./bin/test -gen 5 5 ran -e 0.01

Result | Count | Rank
-------+-------+-------
   182 |     0 |    22
   370 |     0 |    18
   104 |     0 |    23
   606 |     0 |    10
   423 |     0 |    14
   685 |     0 |     6
   723 |     0 |     5
   869 |     0 |     4
    14 |     0 |    25
   393 |     0 |    17
   439 |     0 |    12
   401 |     0 |    16
   641 |     0 |     8
   885 |     0 |     3
   289 |     0 |    20
   217 |     0 |    21
   412 |     0 |    15
   428 |     0 |    13
   344 |     0 |    19
   615 |     0 |     9
   678 |     0 |     7
   500 |     0 |    11
    20 |     0 |    24
   921 |    82 |     2
   949 |   918 |     1
=======================

Trials:
    1000

Iterations per trial:
    min  437
    max  725
    mean 463


$ ./bin/test -gen 5 5 ran -e 0.001

Result | Count | Rank
-------+-------+-------
   182 |     0 |    22
   370 |     0 |    18
   104 |     0 |    23
   606 |     0 |    10
   423 |     0 |    14
   685 |     0 |     6
   723 |     0 |     5
   869 |     0 |     4
    14 |     0 |    25
   393 |     0 |    17
   439 |     0 |    12
   401 |     0 |    16
   641 |     0 |     8
   885 |     0 |     3
   289 |     0 |    20
   217 |     0 |    21
   412 |     0 |    15
   428 |     0 |    13
   344 |     0 |    19
   921 |     0 |     2
   615 |     0 |     9
   678 |     0 |     7
   500 |     0 |    11
    20 |     0 |    24
   949 |  1000 |     1
=======================

Trials:
    1000

Iterations per trial:
    min  6682
    max  6988
    mean 6713
```
