***Latvijas personas koda pareizības pārbaude PYTHON valodā***

Nosacījumi, personaas kods ir LV, ja:
1)	Atbilst šablonam kur visas rakstus zīmes ir cipari vai domuzīme pēc 6 rakstu zīmes (domuzīme var arī nebūt personas koda ievadā)
2)	No pirmajiem 6 personas koda cipariem var iegūt derīgu dzimšanas datumu
3)	Personas koda visu ciparu izņemot pēdējot kontrolsumma atbilst pēdējam personas koda ciparam

**Instalācija:**
pip install git+https://github.com/stuzeneger/LVPKUtils.git 

**Lietošana:**
import lvpkutils
lvpkutils.validLVPersonCode("161177-11495")
True

**Izmatots PYTHON kodā:**
Regex, datetime, enumerate, lambda
