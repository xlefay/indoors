# Indoors

This is a small shell script that'll take the output of the 'uptime' command
and transform it somewhat. I was inspired by the following quote:

    <Black_Prince> I haven't left house for 7 days now!
    <Black_Prince> :D
    <AdmiralA> oh great, people are bragging about not going outside like it's uptime now
    <AdmiralA> $ indoors
    <AdmiralA> 21:40 not seen light in 2 days, 6:39, 3 meals, kcal averages: 0.23 0.13 0.09
    - Source: http://www.qdb.us/307755

Simply run the 'install' script as root:

```bash
$ sudo sh install.sh
```

Now, if all went well, you can enjoy your new shiny indoors command, give it a
try:

```bash
$ indoors
```

The output should be similar to:

```bash
$ indoors
06:56:45 not seen light in 5 days, 12:09, 7 meals, kcal average: 2.13, 2.14, 2.14
$
```

Enjoy!
