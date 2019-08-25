# Alkusanat
Omia muistiipanoja Roux-menetelmään liittyen. Pohjana Kian Mansourin nelivaiheinen ohje Roux-menetelmästä aloittelijoille.

# Kaksi ensimmäistä vaihetta
Vasemmalle tehdään 1x2x3 lohko. Sininen vasemmalle, punainen eteen. Oikealle tehdään toinen 1x2x3 lohko. Edellistä väriesimerkkiä seuraten, vihreä tulee nyt oikealle.<br>
<div class="algorithm-container">
    <div class="algorithm">1. vaihe</div>
    <div class="roofpig algorithm-visual" data-config="colored=U-|solved=UL-|setupmoves=y'"></div>
</div>
<div class="algorithm-container">
    <div class="algorithm">2. vaihe</div>
    <div class="roofpig algorithm-visual" data-config="colored=U-|solved=F DF D"></div>
</div>
<div class="spacer"></div>

# Kolmas vaihe
Käännetään ja siirretään (orient & permute) yläkerroksen kulmapalat kohdalleen.
<div class="algorithm-container">
    <div class="algorithm">U - Headlights</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' F'"></div>
    <div class="algorithm">F (R U R' U') F'</div>
</div>
<div class="algorithm-container">
    <div class="algorithm">Pi - Bruno</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' F'"></div>
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
    <div class="algorithm">R U2 R' U' R U2<br>L' U R' U' L</div>
</div>

<div class="algorithm-container">
    <div class="algorithm">Y-Perm<br>(ULB <-> URF)</div>
    <div class="roofpig algorithm-visual" data-config="solved=U-|colored=URF ULF URB ULB|alg=F R U' R' U' R U R' F' R U R' U' R' F R F'"></div>
    <div class="algorithm">F R U' R' U' R<br>U R' F' R U R'<br>U' R' F R F'</div>
</div>

<div class="spacer"></div>

# Neljäs vaihe
Neljäs vaihe koostuu kolmesta alivaiheesta:
1. Käännetään kuusi viimeistä reunapalaa käyttäen vain M- ja U-siirtoja. Tämän jälkeen UF, UB, UL, UR, DF ja DB on käännetty oikein päin.
1. Laitetaan UL ja UR oikeille paikoilleen säilyttäen ne oikein päin. Tämän vaiheen jälkeen vasemman ja oikean sivun pitäisi olla täysin valmiita.
1. Ratkaistaan reunat ja keskustat M-viipaleessa käyttäen pelkästään M- ja U2-liikkeitä.
    - “Bars, columns & dots”
    - Bars: white & yellow bar: **M2 U2 M2 U2**
    - Columns: red & orange bar: **M’ U2 M2 U2 M’**
    - Dots: **E2 M E2 M'**
