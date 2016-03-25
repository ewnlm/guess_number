# guess\_number

This is a game for guessing the numbers. There are 4 digits no repeat numbers 0~9.
The file *golden.txt* is our input pattern as golden. The program will to guess the golden
pattern by multiply iterations with some algorithms. 

The symbol *A* mean the right number and correct location. Symbol *B* indicate rigth 
number but incorrect location. If we get the completely match we get the *4A* and its
amount of total iteration.

# Usage
```perl
./guess_nu
```

# Reviews
1.  Unique array
    ```perl
    my @ary = (1,2,3,2,3);
    my %seen;
    my @uniq = grep !$seen{$_}++ @ary;
    ```
