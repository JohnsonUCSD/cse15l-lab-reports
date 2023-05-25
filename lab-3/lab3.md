# **Lab Report 3: Grep Command-line Options**
Source used for all: [https://www.geeksforgeeks.org/grep-command-in-unixlinux/#](https://www.geeksforgeeks.org/grep-command-in-unixlinux/#)

## Using -w
`$ grep -w Daniel  government/Alcohol_Problems/DraftRecom-PDF.txt`
!Image[grepw1.png]

`$ grep -w Salt  government/Media/5_Legal_Groups.txt`

The `-w` option searches for the whole word in each line of the .txt file. This is useful some substrings may have the word in it such as how "service" has the substring "vice" in it, so when you don't have the `-w` and look for "vice" with grep it makes it so that it returns the line with the word "service" in it.

## Using -n
`$ grep -n "recently" plos/journal.pbio.0020001.txt`

`$ grep -n "American" 911report/chapter-1.txt`

The `-n` option is like a normal grep but adds the line numbers of where it found the specifc line. This is useful because you might want to look for a specific string or word being used and reading the content surrounding the word such as when a specific name is mentioned.

## Using -c
`$ grep -c "American" 911report/chapter-1.txt`

`$ grep -c "American" 911report/chapter-10.txt`

The `-c` option makes it so that it returns the number of lines with the specific string. This is useful because in large files with long lines, it would be hard to manually count each line, and with the `-c` it counts it all easily for you.

## Using -l
`$ grep -l "Boston" 911report/*.txt`

`$ grep -l "cholesterol" biomed/*.txt`

The `-l` option makes it so that it returns the file names with the specific string you want to search for. This is very useful because if you have many text files and want are looking for a specific string in them, you can just use `-l` to narrow it down to the files that actually have the string.
