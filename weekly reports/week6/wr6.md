---
Angel Rodriguez
Week report 5
---
## Wildcards
* Wildcard represents letters and characters used to specify a file name for searches. You can use a wild card to get a long list of all files in the current directory.
* The * wildcard it matches anything and nothing and matches any number. You should use the * wildcard when you want to list all files with a particular file extension.
* The ? wild card matches with one character. It proves very useful when working with hidden files.
* The [] wild card matches a single character in range. 
## Brace expansion
* It is not a wildcard but it is another feature of bash that allows you to generate strings with commands. 
## Example of brace expansion
* mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1...3}
