*Testauscolorizer* näyttää kotikuntien suhteellisen yleisyyden

Minimalistinen ulkonäkö tarkoituksella
- ei kerro asukkaiden lukumäärää
- ei anna kunnan nimeä
- tyylikäs

Pääosin pohjana käytetty mapcolorizer.js ([kuntakartta.org](http://kuntakartta.org)), ajantasaisempi kuntajako on peräisin [Teemu Koiviston Map of Finlandista](https://github.com/TeemuKoivisto/map-of-finland).

Tämä oli testi, saako ilman mitään koodaustaitoja aikaiseksi jotain mikä miellyttää itseä. Näemmä saa.
Koodissa on varmasti minun jäljiltä paljonkin sanomista, saa korjata. Mulla ei ole vastauksia lukuisiin ilmeneviin kysymyksiin, se nyt vaan sattuu toimimaan.

Kartan on tarkoitus toimia jotakuinkin näin:
- liitä laskentataulukkoon halutut kotikunnat (oletuksena vertaa suomenkielisiin nimiin)
- muuta saatu tieto kuntakoodeista ja lukumääristä JSON-muotoon (listan pitäisi olla muodossa `"nro":luku`) ja tallenna kansioon 'data' nimellä 'kotikunta.json'
- sivusto voidaan ajaa paikallisesti site-kansiossa olevalla Python-skriptillä run-wwwserver.sh
