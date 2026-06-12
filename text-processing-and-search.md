# grep

Search for patterns within files.

grep "ERROR" application.log
# awk

Process and analyze structured text data. Data logs must be separated in columns as a pre-requisite.

awk 'NR>=1 && NR<=10 && /WARN/ {print NR, $1}' access.log
# sed

Perform text transformations and replacements.

sed 's/dev/test/g' config.txt
# wc

Count lines, words, and characters.

wc -l application.log
# find

Search for files and directories.

find /var/log -name "*.log"
# sort

Sort lines of text.

sort names.txt
# head

Display the first lines of a file.

head -n 10 app.log
# tail

Display the last lines of a file.

tail -n 10 app.log
# tac

Display file contents in reverse order.

tac app.log
