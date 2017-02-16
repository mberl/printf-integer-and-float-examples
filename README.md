#Integer and float examples using printf
It's not always easy to remember how to use printf with integers (%i) and floats (%)

Here is some examples to clear up your mind

## Integer

These exmaples prints out a integer that use minimum 3 digits or space(s) if less:

```
printf %3i 555
555
```

```
printf %3i 5
  5
```

The next example will replace space(s) with zero:

```
printf %.3i 5
005
```

## Float

These examples prints out a float with 3 decimals regardless if you use a integer (5) or float (5.55555):

```
printf %.3f 5
5.000
```
```
printf %.3f 5.55555
5.556
```

As you see it use rounded number so the last decimale is 6.

Then here is a couple of examples that prints out with spaces or zeros so the output fit 5 digits (include .):

```
printf %5.1f 5.12345
  5.1
```

```
printf %05.1f 5.12345
005.1
```
