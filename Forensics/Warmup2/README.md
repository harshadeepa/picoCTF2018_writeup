# Warmup 2
Points: 50

## Category
Forensics

## Question
>Hmm for some reason I can't open this [PNG](file/flag.png)? Any ideas? 

### Hint
>How do operating systems know what kind of file it is? (It's not just the ending!
>Make sure to submit the flag as picoCTF{XXXXX}

## Solution
hit `file flag.png` to find the actual file type, which turns out to be jpeg.

change the file extension to _.jpeg_

try viewing the image and you get the flag

### Flag
`picoCTF{extensions_are_a_lie}`
