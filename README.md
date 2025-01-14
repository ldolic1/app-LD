# app-LD
https://github.com/ldolic1/app-LD

SELECT knjiga.naslov
FROM knjiga
JOIN autor ON knjiga.autor = autor.id
WHERE autor.prezime_ime = 'Brlic-Mazuranic Ivana'
ORDER BY knjiga.naslov ASC;
