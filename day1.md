#Day 1 - cat

######resources: man cat & [www.Linfo.org/cat.html](www.Linfo.org/cat.html)

---
###You can use cat to:
con*cat*enate files

read files (cat [filename])

###Use:
cat [OPTION] [FILE] (sometimes need to add a direction & destination)

###One Thing:
concatenate files

###Use case:
You have all the text messages between your BFF Mariah that you've saved in one file for each month and you want to combine them into a file to print for her birthday.
The file will be called "MariahTexts.txt"

CD to BFF
`roxy@roxy-pc:~$ cd BFF`

The directory has in it Jan.txt, Feb.txt, Mar.txt, and Apr.txt

time to run cat!
`roxy@roxy-pc:~$ cat Jan.txt Feb.txt Mar.txt Apr.txt > Mariahtexts.txt`

Now you have one file with all the texts!

###But wait, there's more!
You can also pipe commands with cat like:
more

less

sort

grep

uniq

and more...

even...

ssh!

