Ši programa leidžia vartotojui pasirinkti ar bus generuojami failai su studentais ar atliekamas testavimas su prieš tai sugeneruotais failais. Pasirinkus generavimą vartotojas turi pasirinkti ar bus naudojamas vector konteineris, ar list konteineris. Tada yra generuojami penki atsitiktiniai studentų sąrašų failai, sudaryti iš: 1 000, 10 000, 100 000, 1 000 000, 10 000 000 įrašų. . Pasirinkus testavimą vartotojas taip pat turi pasirinkti ar bus naudojamas vector konteineris, ar list konteineris. Tada yra nuskaitomi jau sugeneruoti failai, atliekamas rūšiavimas pagal balus į "vargšiukai" (galutinis balas< 5) ir kietiakai" (galutinis balas > 5) ir išvedami surūšiuoti studentai į atskirus failus.. Taip pat matuojame veikimo spartą priklausomai nuo naudojamo vieno iš dvejų konteinerių vector ar list, kad duomenys būtų tikslesni yra sukurtas ciklas, kuris leidžia funkcijas 3 kartus ir imame rezultatų vidurkį. Šia programa siekiama palyginti darbą su struct ir class.

Naudojant struct:

<img width="712" alt="struktura_vector" src="https://github.com/edabarsteigaite/antras/assets/145291058/e50ac92f-0c2b-4407-9511-a62a9c3d0474">

Naudojant class:

<img width="745" alt="klase_vector" src="https://github.com/edabarsteigaite/antras/assets/145291058/26381fa4-f82e-4080-bfd9-59c6a8e39dc3">

Taigi, naudojant class veikimo laikas yra ilgesnis.

Eksperimentinė analizė priklausomai nuo kompiliatoriaus optimizavimo lygio:
O1:

<img width="745" alt="klase_o1" src="https://github.com/edabarsteigaite/antras/assets/145291058/67593b91-4481-4391-bef0-39f3d6915440">

O2:

<img width="724" alt="klase_o2" src="https://github.com/edabarsteigaite/antras/assets/145291058/03af9e51-536a-4aef-8246-0f8a91316a36">

O3:

<img width="728" alt="klase_o3" src="https://github.com/edabarsteigaite/antras/assets/145291058/7738954d-9c6f-40c8-93da-d82da7df844a">

Dirbant su skirtingais flag programos veikimo laikas labai panašus, bet O1 buvo pats sparčiausias. Visų exe failų dydis buvo vienodas 1,251 KB 
Testavimas vykdytas su šiais parametrais: Procesorius: AMD Ryzen 7 5800H with Radeon Graphics 3.20 GHz, Atmintis: 16.0 GB (13.9 GB naudojama), SSD

