# Alkusanat
Omia muistiipanoja Roux-menetelmään liittyen.

<style>
.rp160 { width: 160px; height: 180px; }
.rp170 { width: 170px; height: 203px; }
.rp250 { width: 250px; height: 299px; }
.rp440 { width: 440px; height: 499px; }
.left { float: left; }
</style>

<script>
    ROOFPIG_CONF_P1 = "colors=cube:white|hover=1.8";
    ROOFPIG_CONF_F4 = "solved=UR-|colors=F:b B:g U:r D:o R:w L:y c:#666|colored=U UL-";
    ROOFPIG_CONF_F5 = "solved=U- |colors=F:b B:g U:r D:o R:w L:y";
</script>

<h1>RoofPig sample cubes.</h1>
<h3>Official release version</h3>

<body>
<div class="roofpig rp250 left" data-config="base=P1|solved=UFR*|tweaks=XxX:UFR BBB:UBR|flags=showalg|alg=D'+D> R>+R' D R' D' R2|algdisplay=fancy2s Z"></div>
<div class="roofpig rp170 left" data-config="base=P1|flags=canvas showalg startsolved|alg=F L F U' R U F2 L2 U' L' B D' B' L2 U|pov=dbR"></div>
<div class="roofpig rp440 left" data-config="base=P1|hover=far|flags=showalg|alg=L2 D U2 B2 L B> U'+U> F U' F U' F' L> U>> U' F2 UZ R2 U F R' F' R F' R2 F R' F R F' R2 F D R2 D' R' D R D' R' D R' D' R2|algdisplay=fancy2s 2p"></div>

<div>
  <table>
    <tr>
      <td>
        <div class="roofpig rp160" data-config="pov=Ufr| solved=f| colored=R*/c L*/c| alg= |tweaks=X:Uf x:Dl RF:DL| hover=far ">Undrifted</div>
      </td>
      <td>
        <div class="roofpig rp160" data-config="pov=Ufr| solved=f| colored=R*/c L*/c| alg=y |tweaks=X:Uf x:Dl RF:DL| hover=far ">Drifted</div>
      </td>
      <td>
        <div style="height:235px; width: 190px;" class="roofpig" data-config="alg=M M' x y2 z' E E' S S' M E S M E S|flags=showalg"></div>
      </td>
      <td>
        <div class="roofpig rp160" data-config="hover=none|speed=200|alg=L2 D U2 B2 L B> U'+U> F U' F U' F' L> U2 U' F2 UZ R2 U F R' F' R F' R2 F R' F R F' R2 F D R2 D' R' D R D' R' D R' D' R2"></div>
      </td>
      <td><div style="height:125px; width: 100px;" class="roofpig" data-config="base=F4|setupmoves=R' U R U|alg=R' U R U' R U2 R U2 R2"></div></td>
    </tr>
  </table>
</div>

<script src="jquery-3.1.1.min.js"></script>
<script src="roofpig_and_three.min.js"></script>
