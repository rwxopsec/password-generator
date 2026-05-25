# password-generator
Projekto roles ir darbų pasidalinimas
Projektas: Advanced Password Generator
Pradinis kodas: GitHub PassGen.py
Nuoroda: https://github.com/Aewass/Python-Password-Generator-w-TKinter-GUI/blob/master/PassGen.py

Bendras tikslas
Patobulinti slaptažodžių generatorių su tkinter grafine sąsaja. Kad projektas
atrodytų kaip realus pirmo kurso komandinis darbas, kodas padalintas į tris
dalis. Kiekvienas komandos narys turi po 2 pagrindines funkcijas ir maždaug
panašų kiekį kodo.

Eligijus atsakingas už slaptažodžio generavimo logiką.

Jo funkcijos kode:

get_selected_characters() - surenka vartotojo pasirinktus simbolius: raides, skaičius ir simbolius;
generate_password() - sugeneruoja slaptažodį, patikrina ilgį ir perduoda rezultatą kitoms programos dalims.
Ką jis keitė:

random generavimą pakeitė į saugesnį secrets;
pridėjo tikrinimą, ar pasirinkta bent viena simbolių grupė;
padarė, kad slaptažodyje būtų bent vienas simbolis iš kiekvienos pasirinktos grupės;
pridėjo klaidų tikrinimą, jei vartotojas įveda netinkamą ilgį.

Tomas atsakingas už programos langą, išdėstymą ir dizainą.

Jo funkcijos kode:

create_window() - sukuria pagrindinį programos langą;
create_interface() - sudeda tekstus, įvesties laukus, mygtukus, istorijos sąrašą ir tamsų dizainą.
Ką jis keitė:

pradinį šviesų dizainą pakeitė į tamsų cyber / hacker stilių;
pridėjo žalią terminalo tipo tekstą;
sukūrė aiškų išdėstymą su nustatymais, rezultatu ir istorija;
pasirūpino, kad programa atrodytų tvarkingai, bet kodas nebūtų per sudėtingas.

Matas atsakingas už papildomas funkcijas.

Jo funkcijos kode:

check_strength() - įvertina slaptažodžio stiprumą;
password_actions() - tvarko istoriją, kopijavimą, išsaugojimą ir istorijos išvalymą.
Ką jis keitė:

pridėjo slaptažodžio stiprumo įvertinimą;
pridėjo slaptažodžių istoriją;
pridėjo kopijavimą į iškarpinę;
pridėjo istorijos išsaugojimą į failą slaptazodziu_istorija.txt;
pridėjo istorijos išvalymą.
Kodo pasidalinimo logika
Kode yra trys aiškiai pažymėtos dalys:

ELIGIJAUS DALIS;
MATO DALIS;
TOMO DALIS.
Taip per pristatymą galima lengvai parodyti, kuris komandos narys už ką buvo
atsakingas. Kiekviena dalis turi po 2 pagrindines funkcijas, todėl darbas
atrodo tolygiai padalintas.
