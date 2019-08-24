# Alkusanat
Omia muistiipanoja Roux-menetelmään liittyen. Pohjana Kian Mansourin nelivaiheinen ohje Roux-menetelmästä aloittelijoille.

# Kaksi ensimmäistä vaihetta
Vasemmalle tehdään 1x2x3 lohko. Sininen vasemmalle, punainen eteen. Oikealle tehdään toinen 1x2x3 lohko. Edellistä väriesimerkkiä seuraten, vihreä tulee nyt oikealle.<br>
<div class="roofpig cube-box table-cell" data-config="colored=U-|solved=UL-|setupmoves=y'">1. vaihe</div>
<div class="roofpig cube-box table-cell" data-config="colored=U-|solved=F DF D">2. vaihe</div>
<div class="spacer"></div>

# Kolmas vaihe
Käännetään ja siirretään (orient & permute) yläkerroksen kulmapalat kohdalleen.
<div class="roofpig cube-box" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' F'">U - Headlights<div>F (R U R' U') F'</div></div>
<div class="roofpig cube-box" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' R U R' U' F'">Pi - Bruno<div>F (R U R' U')x2 F'</div></div>
<div class="roofpig cube-box four-lines" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=F R U R' U' R U R' U' R U R' U' F'">H - Double Headlights<div>F (R U R' U')x3 F'</div></div>

<div class="roofpig cube-box four-lines" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R U2 R' U' R U R' U' R U R' U' R U' R'">L-case - Bowtie<div>R U2 R' U'</div><div>(R U R' U')x2</div><div>R U' R'</div></div>
<div class="roofpig cube-box four-lines" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R U R' U' R' F R F'">T - Blinkers, Chameleon<div>(R U R' U')</div><div>R' F R F'</div></div>
<div class="roofpig cube-box" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R U R' U R U2 R'">Sune<div>R U R' U R U2 R'</div></div>

<div class="roofpig cube-box" data-config="solved=U-|colored=Ufr Ufl Ubl Ubr|alg=R' U' R U' R' U2 R">Anti-Sune<div>R' U' R U' R' U2 R</div></div>
<div class="roofpig cube-box six-lines" data-config="solved=U-|colored=URF ULF URB ULB|alg=R U2 R' U' R U2 L' U R' U' L">J-Perm<div>(vaihtaa URB URF)</div><div>R U2 R' U' R U2</div><div>L' U R' U' L</div></div>
<div class="roofpig cube-box six-lines" data-config="solved=U-|colored=URF ULF URB ULB|alg=F R U' R' U' R U R' F' R U R' U' R' F R F'">Y-Perm<div>(vaihtaa ULB URF)</div><div>F R U' R' U' R</div><div>U R' F' (R U R' U')</div><div>R' F R F'</div></div>
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
