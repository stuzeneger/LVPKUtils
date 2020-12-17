***Latvijas personas koda pareizības pārbaude PYTHON valodā***

Nosacījumi, personaas kods ir LV, ja:<br>
1)	Atbilst šablonam kur visas rakstus zīmes ir cipari vai domuzīme pēc 6 rakstu zīmes (domuzīme var arī nebūt personas koda ievadā)<br>
2)	No pirmajiem 6 personas koda cipariem var iegūt derīgu dzimšanas datumu<br>
3)	Personas koda visu ciparu izņemot pēdējot kontrolsumma atbilst pēdējam personas koda ciparam<br>

**Instalācija:**<br>
pip install git+https://github.com/stuzeneger/LVPKUtils.git 

**Lietošana:**<br>
import lvpkutils<br>
lvpkutils.validLVPersonCode("161177-11495")<br>
True<br>

**Izmatots PYTHON kodā:**<br>
Regex, datetime, enumerate, lambda
