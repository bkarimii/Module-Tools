The `grep` command in Linux is used to search for specific patterns in a file or output.

Basic syntax:
grep [options] "pattern" filename

Commonly used flags:
-c → Counts the number of lines that match the pattern.
-F → Treats the search pattern as a fixed string (not a regular expression).
-r → Recursively searches through directories.
-v → Inverts the match (shows lines that do NOT contain the pattern).
-l → Lists only the filenames that contain the pattern.
-o → Displays only the matching parts of the lines, not the whole line.

Context flags:
-A N → Shows N lines **after** a matching line.
-B N → Shows N lines **before** a matching line.
-C N → Shows N lines **before and after** a matching line.

Examples:

1. Search for "error" in a log file:
   grep "error" logfile.txt

2. Count occurrences of "warning" in a file:
   grep -c "warning" logfile.txt

3. Find "TODO" in all `.txt` files in a directory (recursively):
   grep -r "TODO" /path/to/directory

4. Show 3 lines after a match:
   grep -A 3 "error" logfile.txt

5. Show files that contain "success":
   grep -l "success" \*.log

The `grep` command is a powerful tool for searching and filtering text in Linux!
