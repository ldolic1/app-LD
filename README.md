# app-LD
https://github.com/ldolic1/app-LD
SELECT knjiga.naslov
n/FROM knjiga
n/JOIN autor ON knjiga.autor = autor.id
n/WHERE autor.prezime_ime = 'Brlic-Mazuranic Ivana'
n/ORDER BY knjiga.naslov ASC;
