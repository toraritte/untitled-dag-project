# untitled-dag-project

A mostani munkamban is az jellemzo, hogy kulonbozo helyekrol (adatbazis, file, tool) szedem ossze, amit tudni akarok
Amivel Te szembesulsz szerintem az intezetben, az is ilyen. Itt igy csinaljak, ott ugy. Itt ezzel a toollal, ott azzal
share-eltem, amit elkezdtem irni

A vision-ban ezeket szeretnem kiemelni:
- egy tool, amiben tobbfele fuggosegi kapcsolatokat tudsz eltarolni tudasbeli vagy munkafolyamatbeli allapotok kozott
- ezek megjelenitese iranyitott grafszeru legyen, amiben a fuggosegek a nyilak, az allapotok a csucsok es barmelyik cimkezheto a kesobbi ujrahasznositas es kereses miatt
- az egesz tarolasa dag-ban legyen
- ezt egy csapat tudja hasznalni, tehat hozzaferheto legyen kozponti helyen mint website es cmdlinebol is
- a meglevo elemi kapcsolatok az allapotok kozott hasznalhatok legyenek eljarasok, parancsok megjelenitesere es futtatasara
- legyen a toolnak egy olyan interface-e, API-ja, amivel scriptnyelveken (perl) lehet hasznalni es manipulalni az infot benne
- a Te es en dolgaimra hasznalhato valtozat szulessen fel even belu
Ehhez hozzairnad, amit Te is belelatsz ebbe az eddigiek alapjan? Utana osszehozunk egy velos valtozatot

- processz topologiai diagnosztika
  (Felmerni a fuggosegeket a processzek kozott - melyik process fugg melyiktol, es milyen servicek kellenek az eleresukhoz vagy hogy honnan lehet oket elerni. 
  Ha megvan a topologia, akkor lehet automatizalni a resource-ok elereset, es/vagy alapkent lehet hasznalni arra, hogy rendet tehessunk a rendszerben (ha a korulmenyeink engedik)
- kovetelmeny felmeres - egy adott rendszer mukodik, de extra koroket kell futni valaminek az elintezesehez, ami teljesen folosleges, de ezzel a modszerrel be lehetne merni ezeket az extra lepeseket majd eliminalni
- barmilyen processt fel lehetne igy merni, hogy mekkora utat kell bejarni a kezdoponttol a feladat vegeig. Pl felvesznek egy uj tanulot, van egy csomo formasag amit el kell intezni, es igy kiderulne, hogy mi a felesleges vagy alapvetoen rossz megkozelites
