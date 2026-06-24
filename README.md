<img src="./img/logo_inverz.png" alt="Budapesti Corvinus Egyetem" width="300" />

> [!CAUTION]
> **Nem hivatalos egyetemi sablon**, a szakdolgozat leadási követelményeinek való megfelelés nem minden esetben garantált, leadás előtt érdemes ellenőrizni a mindenkori hatályos TVSZ-ben foglaltakat!  
> TVSZ 2024.07-től: https://www.uni-corvinus.hu/downloads/98n7.tnm69v/hkr-3-tvsz-2024-szeptember-1-00-alairt-1.pdf

# Budapesti Corvinus Egyetem LaTeX szakdolgozati sablon

Szakdolgozati sablon azon hallgatók számára, akik szakdolgozatukat LaTeX környezetben készítik.  
Pontosabb leírást és példákat a `main.pdf` fájl tartalmaz!

### Telepítési útmutató

A sablon telepítéséhez elég letölteni a `bce-thesis.cls` fájlt, viszont a legegyszerűbb használathoz érdemes az egész tárhelyet klónozni.

```
git clone https://github.com/m-marcell/bce-thesis
```

A dolgozatot `pdflatex` enginnel érdemes fordítani. Csak a `main.tex` fájlt kell fordítani, a szekciókhoz létrehozott egyedi `.tex` fájlok autómatikusan importálva lesznek.

### Hasznos linkek és információk a LaTeX programcsomaghoz

A LaTeX használatához **rendelkezni kell telepített Tex környezettel**, például Windows: [MiKTeX](https://miktex.org/), MacOS: [MacTeX](https://tug.org/mactex/), Linux: [TeX Live](https://tug.org/texlive/).

Hasznos anyagok kezdőknek és haladóknak:
- LaTeX alapok ELTE (quick start): https://people.inf.elte.hu/alagi/elte/bevinfo/latex.htm
- BME latex: https://math.bme.hu/latex/
- LaTeX kezdőknek és haladóknak (könyv): https://tibortomacs.github.io/latex-tutorial-hu/latex.pdf
- Latex Cheet Sheet: https://quickref.me/latex

Továbbá hasznos forrás lehet a [csomagok archívuma](https://ctan.org/), de sima internetes keresés után is sok jó forrás és példa áll rendelkezésre!

### Egyéni változtatások

A szakdolgozat formaterve a `bce-thesis.cls` fájlban található, az egyéni változtatásokat itt lehet központilag megtenni! Egyelőre class fájlként üzemel, idővel elképzelhető, hogy különálló csomagként is betölthető legyen.

### Nyilatkozat

Az új egyetemi szabályozás szerint a leadott szakdolgozatokhoz csatolni kell egy mesterséges intelligencia használatról szóló nyilatkozatot, ahol részletezni kell, hogy milyen mértékben és mely feladatokhoz használt a hallgató AI eszközöket. Ez a nyilatkozat jelenleg a `bce-thesis.cls` fájlban szerkeszthető!

------

A változtatási javaslatokat és egyéb közreműködéseket örömmel fogadom. Jó munkát a szakdolgozathoz!
