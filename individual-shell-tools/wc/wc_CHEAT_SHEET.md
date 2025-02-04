The `wc` (word count) command in Linux is used to count lines, words, and bytes in a file.

Basic usage:
wc [options] filename

Flags:
-c → Counts the number of bytes (or characters) in a file.
-l → Counts the number of lines in a file.
-w → Counts the number of words in a file.

Examples:

1. Count lines in a file:
   wc -l filename.txt

2. Count words in a file:
   wc -w filename.txt

3. Count bytes in a file:
   wc -c filename.txt

4. Count everything (lines, words, and bytes):
   wc filename.txt

It’s a simple and useful command for analyzing text files in Linux!
