# *Palvelinten hallinta tehtävä 3. Versionhallinta, markdown,  salt*

## a) Git ja Markdown
Tässä tehtävässä oli määrä harjoitella paitsi markdownin käyttöä myös versionhallintaa gitin ja githubin avulla. Githubista on hieman kokemusta, lähinnä tietokantakurssilta, markdownista ei oikeastaan kokoemusta ole. Tehtävässä päästiin tavallaan alkuun jo tunnilla,
 kun kävimme läpi git:in peruskomentoja, ja katsoimme alustavasti githubia. Itseltäni löytyikin jo valmiiksi github tili, johon loin repositorion tätä tehtävää varten. Ohjeita tehtävää varten katselin pääosin Tero Karvisen [sivuilta](http://terokarvinen.com/2016/publish-your-project-with-github/). ALkutoimenpiteissä seurasin sivun ohejita pilkulleen, mutta vaihdoin salansananmuistamisen ajan hieman pidemmäksi, komentona siis ´<$ git config --global credential.helper "cache --timeout=7200">´, jossa 7200 = sekunnit jotka salasana on voimassa. 

Tärkää tässä on siis ymmärtää git:in perustoiminto. Itse tein siinä järjesteyksessä, että loin aluksi repositorion, jonka cloonasin git clone -komennolla omaan, Xubuntu kotikansiooni. Loin sinne tiedostot jotka halusin luoda, testitiedoston, ja tämän palautustiedoston .md päätteiillä, jotta github tunnistaa nämä markdown -muotoiluiksi. Kun muutokset on tehty, ne lisätään ikäänkuin jonoon git add komennolla, git commit vahvistaa että haluan lähettää tiedostot. Tiedostot ovat kuitenkin toistaiseksi vain paikallisesti taltioitu Git push komennon antaminen syöttää tiedostot verkkoon, sen jälkeen kun on syöttänyt tunnuksensa. Sivuilta löytyikin ritiramssu sitä varalta, että haluaa tehdä kaiken yhdessä pätkässä. Git pull hakee ymmärtääkseni tiedot verkosta ja synkronoi ne paikallisen repon kanssa. 
`<$ git add . && git commit; git pull && git push>` Mardownn on githubissa kätevä, sillä muotoilu tapahtuu automaattisesti. Hiukan oli kuitenkin vaikeuksia saada esim linkki toimimaan (väärä määrä välilyöntejä ehkä?), ja koodimuotoon muotoilussa olivat hipsut vääränlaiset. Onneksi nanon käyttö on tuttua aiemmalta linux-kurssilta, joten sen osalta ei suurempia ihmettelemisiä syntynyt.

## b) Git Log, Git Diff, Git Blame
Nyt kun perustoiminallisuus oli kunnossa, kokeilin tehtävässä mainittuja komentoja. Hain hieman tukea jo valmiiksi internetistä, että osaisin hiukan arvioida mitä pitäisi tapahtua, lähteenä käytin lähinnä git.scm.com -sivun hakemistoa. Komennoista löytyy kuvia tästä git-reposta. 

Git Log ainakin kertoo sen, mitä muutoksia tiedostoon/ tiedostoihin on tehty, ja milloin. Se myös näyttää tekijän ja sähköpostiosoitteeni. 

 
