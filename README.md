Ši programa skirta studentų duomenų įvedimui, generavimui, nuskaitymui iš failo
ir jų analizavimui, įskaitant rūšiavimą, grupavimą, bei išvedimą į skirtingus failus.
Apskaičiuojamas vidurkius ir medianas, studentai išrušiuojami pagal didėjantį/mažėjantį 
vidurkį ir suskirstomi į kategorijas "kietiakai" ir "vargšiai".
Yra du programos kodai viename naudojami vektoriai, kituose listai, atlikus analizę ir 
paskaičiavus programos veikimo laiko vidurkius pastebime, kad programos veikimas 
naudojant listus užtrunka daug ilgiau nei vektorius.

Testavimo sistemos parametrai:
- CPU: 11th Gen Intel® Core™ i7-11800H @ 2.30 GHz
- RAM: 8.00 GB
- SSD: Micron_2400_MTFDKBA512QFM

| 1000 studentų         | Vektorius  | Listas     |
|-----------------------|------------|------------|
| Failo nuskaitymas     | 0.00506 s  | 0.03374 s  |
| Rūšiavimas            | 0.00015 s  | 0.00028 s  |
| Dalijimas į grupes    | 0.00023 s  | 0.00028 s  |
| Vargšių išsaugojimas  | 0.00498 s  | 0.02096 s  |
| Kietekų išsaugojimas  | 0.00204 s  | 0.01257 s  |
| Bendras laikas        | 1.50272 s  | 1.84917 s  |

| 10000 studentų        | Vektorius  | Listas     |
|-----------------------|------------|------------|
| Failo nuskaitymas     | 0.02669 s  | 0.10784 s  |
| Rūšiavimas            | 0.00082 s  | 0.002  s   |
| Dalijimas į grupes    | 0.00087 s  | 0.002 s    |
| Vargšių išsaugojimas  | 0.01624 s  | 0.1117 s   |
| Kietekų išsaugojimas  | 0.01561 s  | 0.0692 s   |
| Bendras laikas        | 1.03115 s  | 2.5817 s   |

| 100000 studentų       | Vektorius  | Listas     |
|-----------------------|------------|------------|
| Failo nuskaitymas     | 0.25901 s  | 0.5901 s   |
| Rūšiavimas            | 0.00667 s  | 0.0304 s   |
| Dalijimas į grupes    | 0.00877 s  | 0.0516 s   |
| Vargšių išsaugojimas  | 0.14073 s  | 0.3413 s   |
| Kietekų išsaugojimas  | 0.14540 s  | 0.4064 s   |
| Bendras laikas        | 1.12741 s  | 2.5918 s   |

| 1000000 studentų      | Vektorius  | Listas     |
|-----------------------|------------|------------|
| Failo nuskaitymas     | 2.65807 s  | 5.4135 s   |
| Rūšiavimas            | 0.07008 s  | 0.8598 s   |
| Dalijimas į grupes    | 0.11358 s  | 0.5529 s   |
| Vargšių išsaugojimas  | 1.41486 s  | 2.8269 s   |
| Kietekų išsaugojimas  | 1.44917 s  | 3.0424 s   |
| Bendras laikas        | 6.81376 s  | 91.606 s   |

| 10000000 studentų     | Vektorius  | Listas     |
|-----------------------|------------|------------|
| Failo nuskaitymas     | 27.0854 s  | 70.177 s   |
| Rūšiavimas            | 0.85670 s  | 14.633 s   |
| Dalijimas į grupes    | 1.06694 s  | 11.406 s   |
| Vargšių išsaugojimas  | 14.4879 s  | 38.104 s   |
| Kietekų išsaugojimas  | 14.704  s  | 37.76 s    |
| Bendras laikas        | 65.1082 s  | 175.06 s   |
