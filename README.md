Ši programa leidžia vartotojui pasirinkti įvesti duomenis ranka, generuoti duomenis atsitiktinai ar nuskaityti iš tekstinio failo. Pasirinkus duomenų vedimą ranka prašoma įvesti studento vardą, pavardę, namų darbų rezultatus ir egzamino įvertinimą, tada kito studento duomenis iki kol vartotojas suves visus studentus. Kita galimybė generuoti duomenis atsitiktinai, tai vartotojas įveda vardą ir pavardę, o balai yra atsitiktinai sugeneruojami. Pasirinkus duomenis nuskaityti iš failo vartotojas turi įrašyti failo pavadinimą
Programa taip pat leidžia vartotojui pasirinkti atlikti testavimą, tai reiškia bus generuojami failai su studentais ir atliekamas testavimas su prieš tai sugeneruotais failais. Pasirinkus generavimą vartotojas turi pasirinkti ar bus naudojamas vector konteineris, ar list konteineris. Tada yra generuojami penki atsitiktiniai studentų sąrašų failai, sudaryti iš: 1 000, 10 000, 100 000, 1 000 000, 10 000 000 įrašų. . Pasirinkus testavimą vartotojas taip pat turi pasirinkti ar bus naudojamas vector konteineris, ar list konteineris. Tada yra nuskaitomi jau sugeneruoti failai, atliekamas rūšiavimas pagal balus į "vargšiukai" (galutinis balas< 5) ir kietiakai" (galutinis balas > 5) ir išvedami surūšiuoti studentai į atskirus failus.. Taip pat matuojame veikimo spartą priklausomai nuo naudojamo vieno iš dvejų konteinerių vector ar list, kad duomenys būtų tikslesni yra sukurtas ciklas, kuris leidžia funkcijas 3 kartus ir imame rezultatų vidurkį.
Šioje versijoje pritaikyta  "Rule of three" (destruktorius, kopijavimo konstruktorius, kopijavimo priskyrimo operatorius) ir įvesties/išvesties operatoriai bei Vietoje turimos vienos Studentas klasės sukurtos dvi: bazinė (abstrakti) klasė, skirtą bendrai aprašyti žmogų ir tuomet iš jos išvestinė (derived) klasė - Studentas. Padaryta, kad žmogui skirta bazinė klasė būtų abstrakčioji klasė ir nebūtų galima sukurti žmogaus tipo objektų, o tik objektus gautus iš jos išvestinių klasių.

Įvedimas ranka:

<img width="761" alt="Screenshot 2023-12-29 183550" src="https://github.com/edabarsteigaite/antras/assets/145291058/4e5e8bfb-fc88-4cc8-b7e3-d0080db37fb5">

Įvedimas atsitiktinai:

<img width="808" alt="Screenshot 2023-12-29 183748" src="https://github.com/edabarsteigaite/antras/assets/145291058/90ba49c4-12b1-4d77-a186-13a3f8616b0a">

Įvedimas iš failo:

<img width="843" alt="Screenshot 2023-12-29 183919" src="https://github.com/edabarsteigaite/antras/assets/145291058/9f51d6bd-4729-4879-977d-5e75d537e0d3">
<img width="747" alt="Screenshot 2023-12-29 183942" src="https://github.com/edabarsteigaite/antras/assets/145291058/7b1133f0-9275-493c-9b23-820e18629ff2">

Testavimas vykdytas su šiais parametrais: Procesorius: AMD Ryzen 7 5800H with Radeon Graphics 3.20 GHz, Atmintis: 16.0 GB (13.9 GB naudojama), SSD

