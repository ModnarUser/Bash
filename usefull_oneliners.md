
## I. Parse Text File and List all Abbreviations with Number of Occurence
```
cat *.txt | grep -wo "[A-Z]\+\{2,10\}" | sort | uniq -c | sort -gr
```