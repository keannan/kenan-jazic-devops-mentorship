# Level 1
ls # izlistavanje fileova
cat readme # otvaranje filea readme

# Level 2
cat ./- 
# s obzirom da ne mozemo otvoriti file sa nazivom -, moramo ga pozvati kao ./-

# Level 3
cat ./spaces\ in\ this\ filename
# u ovom slucaju akda u nazivu imamo space koristimo \ da ga eliminisemo pri pozivu

# Level 4
ls -la 
# -la koristi iscitavanje svih fileova u ovom slucaju sa tabom sam otkrio ovaj file .hidden

# Level 5
cat ./-file07 
# jedini readable file (moze i drugi nacin preko finda ali posto nema puno fileova :) 

# Level 6
find . -type f -size 1033c ! -executable -exec file {} + | grep ASCII
# find za trazenje 
# type tipe filea
# size velicina filea
# ! -executable negacija 
# grep ASCII da je readable u ASCII kodu

# Level 7

# Level 8

# Level 9

# Level 10
