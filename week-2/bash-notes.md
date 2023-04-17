<!-- Level 1 -->
$ ls # izlistavanje fileova
% cat readme # otvaranje filea readme

% Level 2
$ cat ./- 
<!-- s obzirom da ne mozemo otvoriti file sa nazivom -, moramo ga pozvati kao ./- -->

<!-- Level 3 -->
$ cat ./spaces\ in\ this\ filename
% u ovom slucaju akda u nazivu imamo space koristimo \ da ga eliminisemo pri pozivu

% Level 4
$ ls -la 
 <!-- -la koristi iscitavanje svih fileova u ovom slucaju sa tabom sam otkrio ovaj file .hidden -->

 <!-- Level 5 -->
$ cat ./-file07 
%  jedini readable file (moze i drugi nacin preko finda ali posto nema puno fileova :)  --> --> -->

% Level 6
$ find . -type f -size 1033c ! -executable -exec file {} + | grep ASCII

%  find za trazenje 
%  type tipe filea
%  size velicina filea
%  ! -executable negacija 
%  grep ASCII da je readable u ASCII kodu

<!-- Level 7 -->
$ find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
$ cat /var/lib/dpkg/info/bandi7.password
<!-- ovdje se uz pomoc find / komande trazi u svim folderima file sa specificnim parametrima poslanim kroz -type -user -group -size -->

<!-- Level 8 -->
$ cat data.txt | grep "millionth" 
% trazi se u file-u data.txt preko grepa rijec millionth
<!-- Level 9 -->
$ cat data.txt | tr ' ' '\n' | sort | uniq -u 
<!-- preko dodatnih komandi sort i uniq trazimo jedinstvenu rijec  -->
<!-- Level 10 -->
