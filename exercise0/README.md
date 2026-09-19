Jag löste uppgiften ovan genom att navigera mig till linux1_alexandra_winsnes och sedan gjorde jag mkrdir 03_navifation 04_file_managemnet osv för att skapa mao
mapparna. därefter gick jag in i filerna var för sig och skrev touch README.md i terminalen för att skapa en README.md i varje mapp.
Efter detta pushade jag till github genom att 1: git add . 2: git commit -m "exercise0" 3: git push

fråga b) gjorde jag touch file{0..3 för att skapa filerna, jag missade att de skulle heta file1.md osv så jag ändrade det i efterhand genom att skriva mv file1 file1.md
fråga c) mkdir files och sedan mv file1.md file2.md file3.md files
fråga d) mv file2.md .. för att flytta file2.md tillbaka till files 
ls för att dubbelkolla och sedan cd .. för att gå tillbaka till exercise0
fråga e) echo "hello file2" >> file2.md för att skriva in denna text i file2.md
cat file2.md för att se texten
fråga f) cp file2.md file2.txt för att göra en kopia av file2.md och döpa den till file2.txt
fråga g) cat file2.md file2.txt för att se texten från dessa
fråga h) rm file 2.md file2.txt och sedan rm -r files för att radera alla filer förutom README.md
fråga j) nano README.md för att skriva texten här
