# Alkusanat
Omia muistiipanoja Roux-menetelmään liittyen. Pohjana Kian Mansourin nelivaiheinen ohje Roux-menetelmästä aloittelijoille.
_Vinkki:_ klikkaa/kosketa sivun yläreunan sekoitetta, jolloin se päivittyy.

# Kaksi ensimmäistä vaihetta
Vasemmalle tehdään 1x2x3 lohko. Sininen vasemmalle, punainen eteen. Oikealle tehdään toinen 1x2x3 lohko. Edellistä väriesimerkkiä seuraten, vihreä tulee nyt oikealle.<br>
<div class="algorithm-container">
    <div class="algorithm">1. vaihe</div>
    <div class="roofpig algorithm-visual" data-config="solved=*|tweaks=L:bL B:Bl L:L L:fL F:Fl L:dbL D:Dbl B:dBl L:dL D:Dl D:Dfl F:dFl L:dfL|setupmoves=y'"></div>
</div>
<div class="algorithm-container">
    <div class="algorithm">2. vaihe</div>
    <div class="roofpig algorithm-visual" data-config="solved=*|tweaks=L:bL B:Bl L:L L:fL F:Fl L:dbL D:Dbl B:dBl L:dL D:Dl D:Dfl F:dFl L:dfL R:bR B:Br R:fR F:Fr R:R R:dR D:Dr R:dfR D:Dfr F:dFr D:Dbr B:dBr R:dbR"></div>
</div>
<div class="spacer"></div>

# Kolmas vaihe
Roux-menetelmässä kolmannessa vaiheessa laitetaan yläkerroksen kulmapalot oikeisiin paikkoihin oikeassa asennossa. Sen tekemiseen on olemassa useita algoritmejä, mutta alla olevilla pääsee jo hyvin pitkälle.
<div class="algorithm-container">
    <div class="algorithm">U - Headlights</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' F'"></div>
    <div class="algorithm">F (R U R' U') F'</div>
</div>
<div class="algorithm-container">
    <div class="algorithm">Pi - Bruno</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' R U R' U' F'"></div>
    <div class="algorithm">F (R U R' U')x2 F'</div>
</div>
<div class="algorithm-container">
    <div class="algorithm">H - Double Headlights</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' R U R' U' R U R' U' F'"></div>
    <div class="algorithm">F (R U R' U')x3 F'</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">L-case - Bowtie</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R U2 R' U' R U R' U' R U R' U' R U' R'"></div>
    <div class="algorithm">R U2 R' U'<br>(R U R' U')x2<br>R U' R'</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">T - Blinkers</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R U R' U' R' F R F'"></div>
    <div class="algorithm">(R U R' U')<br>R' F R F'</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">Sune</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R U R' U R U2 R'"></div>
    <div class="algorithm">R U R' U R U2 R'</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">Anti-Sune</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R' U' R U' R' U2 R"></div>
    <div class="algorithm">R' U' R U' R' U2 R</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">J-Perm<br>(URB <-> URF)</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=URF ULF URB ULB|alg=R U2 R' U' R U2 L' U R' U' L"></div>
    <div class="algorithm">R U2 R' U'<br>R U2 L' U<br>R' U' L</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">Y-Perm<br>(ULB <-> URF)</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=URF ULF URB ULB|alg=F R U' R' U' R U R' F' R U R' U' R' F R F'"></div>
    <div class="algorithm">F R U' R' U'<br>R U R' F'<br>R U R' U'<br>R' F R F'</div>
</div>

<div class="spacer"></div>

# Neljäs vaihe
Neljännessä vaiheessa asemoidaan ja käännetään kuusi viimeistä reunapalaa kohdalleen käyttäen vain M- ja U-siirtoja. Neljäs vaihe koostuu kolmesta alivaiheesta:

## 4A - Reunat oikein päin
1. Käännetään kuusi viimeistä reunapalaa käyttäen vain M- ja U-siirtoja. Tämän jälkeen UF, UB, UL, UR, DF ja DB on käännetty oikein päin. Ylä- ja alakerroksissa näkyy vain keltaista tai valkoista väriä. Tähän päästään pyrkimällä saamaan aikaiseksi "nuolenpää": yläkerrokssa on kolme reunapalaa väärä väri näkyvissä ja alakerroksessa on yksi väärä väri näkyvissä. Yläkerroksella olevan nuolen kärki käännetään samalla sivulle kuin alakerroksella oleva yksittäinen reuna. Liikesarja jolla tässä tilanteessa saadaan reunat käännettyä on: `M' U' M'`. Toinen Kianin esittämä liikesarja on `M' U2 M`, jolla UF ja DF vaihtavat keskenään paikkaa.
<div class="algorithm-container">
    <div class="algorithm">Nuolenpää</div>
    <div class="roofpig algorithm-visual" data-config="solved=*|tweaks=U:uB B:Ub R:Dr D:dR B:Db D:dB L:DL D:dL|setupmoves=M' U' M'|alg=M' U' M'"></div>
    <div class="algorithm">M' U' M'</div>
</div>
<div class="algorithm-container">
    <div class="algorithm">UF <-> DF</div>
    <div class="roofpig algorithm-visual" data-config="solved=*|tweaks=U:Uf F:uF D:Df F:dF|setupmoves=M' U2 M|alg=M' U2 M"></div>
    <div class="algorithm">M' U2 M</div>
</div>
<div class="spacer"></div>

## 4B - UL ja UR paikoilleen
Laitetaan UL ja UR oikeille paikoilleen säilyttäen ne oikein päin. Tämän vaiheen jälkeen vasemman ja oikean sivun pitäisi olla täysin valmiita. Tässä pyritään saamaan UL (sinikeltainen) ja UR (vihreäkeltainen) paikoilleen käyttämällä edellisen 4A-vaiheessa esitettyä `M' U2 M'` -liikesarjaa. Idea on, että UL on alhaalla edessä ja UR on alhaalla takana, samaan aikaan kun R-sivun yläreuna on edessä ja L-sivun yläreuna on takana. Tällöin UL ja UR saadaan paikoilleen `M2`-liikkeellä.

## 4C - Viimeiset reunat ja keskustat
Tässä alivaiheessa ratkaistaan reunat ja keskustat M-viipaleessa käyttäen pelkästään M- ja U2-liikkeitä. Kian esittää tähän neljä eri vaihtoehtoa, miten palat voivat olla: _bars_, _columns_, _dots_ ja _cycles_.
- _Bars_: Ylhäällä ja alhaalla on valmiit suorat, väreinä siis keltainen ja valkoinen.
- _Columns_: Tämä on kuten edellinen tapaus. Erona on se, että valmiina ovat punainen ja oranssi suora.
- _Dots_: Tässä alivaiheessa kuutio on muuten ratkaistu, mutta keskilinjan keskipalat eivät ole kohdallaan.
- _Cycles_: TBD. Jos tässä vaiheessa UF, UB ja DB ovät väärin, on ratkaisuna `M U2 M'`.

<div class="algorithm-container">
    <div class="algorithm">Bars</div>
    <div class="roofpig algorithm-visual" data-config="solved=L R|tweaks=L:L R:R|alg=M2 U2 M2 U2"></div>
    <div class="algorithm">M2 U2 M2 U2</div>
</div>
<div class="algorithm-container">
    <div class="algorithm">Columns</div>
    <div class="roofpig algorithm-visual" data-config="solved=L R|tweaks=L:L R:R|alg=M' U2 M2 U2 M'"></div>
    <div class="algorithm">M' U2 M2 U2 M'</div>
</div>
<div class="algorithm-container">
    <div class="algorithm">Dots</div>
    <div class="roofpig algorithm-visual" data-config="solved=L R|tweaks=L:L R:R|alg=E2 M E2 M"></div>
    <div class="algorithm">E2 M E2 M</div>
</div>

<div class="spacer"></div>
# Sekoite
<div class="algorithm-container">
    <div class="algorithm">Sekoite</div>
    <div id="scramble-algorithm-visual"></div>
    <div id="scramble-algorithm" class="algorithm"></div>
</div>
