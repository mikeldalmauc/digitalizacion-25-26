- [Erronka 1 3D Inprimaketa: Gidak eta Tipologien Erakusketa](#erronka-1-3d-inprimaketa-gidak-eta-tipologien-erakusketa)
  - [1) Arazo (erreala) eta helburua](#1-arazo-erreala-eta-helburua)
  - [2) Inprimaketa arauak (talde guztientzat)](#2-inprimaketa-arauak-talde-guztientzat)
  - [3) Tipologiak (taldeen arteko gainjartzerik gabe esleituta)](#3-tipologiak-taldeen-arteko-gainjartzerik-gabe-esleituta)
  - [6) Emaitzak (errepositorioaren egitura)](#6-emaitzak-errepositorioaren-egitura)
  - [Azkarreko egiaztapen-zerrenda (zuzenketarako)](#azkarreko-egiaztapen-zerrenda-zuzenketarako)

# Erronka 1 3D Inprimaketa: Gidak eta Tipologien Erakusketa

**Iraupena:** 3 aste · **2 h/aste**
**Testuingurua:** 3D inprimagailu **bakarra** gelan (gela aktiboa, eskolak martxan).
**Entrega-formatua:** Dena **Markdown**-en, klaseko errepositorioan (fork → commits → **Pull Request**).

---

## 1) Arazo (erreala) eta helburua

3D inprimagailua **gutxi erabiltzen** da. **Orientazio praktikoa** falta da jakiteko **zer** inprimatu eta **nola**. Konponbidea: **gida argiak** eta **erakusketa didaktikoa** sortzea, **adibide-ereduekin** hainbat **tipologiatan** (voladizoak/zubiak, tolerantziak, engranajeak, sareak/flex, loturak/snap-fit, etab.), aukerak eta mugak erakusteko.

**Erronkaren helburua:**
Talde bakoitzak **1 erakusketa-lagin** + **A4 tamainako 1 infografia** ekoitziko du, inprimatutako piezari buruzko informazio eta xehetasunekin.

---

## 2) Inprimaketa arauak (talde guztientzat)

* **Pieza txiki edo ertainak**.
* **Gelako jarduna:** taldeko kide bakarrak, **Teknikari rola**, erabiliko du inprimagailua.
* **Inprimagailua partekatua** da: beste taldeekin **koordina** behar da.
* **Aurre-onarpena**: talde bakoitzak bere pieza proposatuko du eta irakaslearen **feedback/iritzia** jasoko du inprimatu aurretik.

---

## 3) Tipologiak (taldeen arteko gainjartzerik gabe esleituta)

* **Voladizoak/Zubiak (Overhang/Bridges):** 30–60° angeluak; zubiak 10–30 mm.
* **Tolerantziak eta doikuntzak:** pinak/zuloak 0,2–0,6 mm; lerrakorrak vs. presioz.
* **Engranajeak:** **hortz zuzeneko** bikote txikia (modulu txikia) **backlash**/**joko librea** erakusteko.
* **Sareak/Flex:** **pareta mehea** + eredu bat (gyroid/hex) malgutasuna erakusteko.
* **Loturak/Snap-fit:** klip sinplea; **zurruntasuna** vs. **hauskortasuna**.
* **Ehendurak/Erliebeak:** **geruza-altuera**/**ahokearen diametroa** eta **geruzaren orientazioa** ikusgarri.
* **Multikolore/Multimaterial:** inprimagailuak ahalbidetzen badu (filamentu bikoitza edo antzekoa).
* **Taldeak proposatutako beste tipologia bat** (irakaslearekin balidatu).

Erreferentziak:

* [3D ereduen adibideak](https://www.thingiverse.com/)
* [David Malawey](https://www.youtube.com/@davidmalawey)

> Gelako mailan, **tipologia GUZTIAK** estali behar dira.

## 6) Emaitzak (errepositorioaren egitura)

![alt testua](images/image.png)

Ikasgelako errepositorioan, **3D → muestras** atalean, talde bakoitzak **inprimatuko duen erakusketa-ereduaren izenarekin** karpeta bat sortuko du, eta barruan gehituko ditu **markdown fitxategia**, **diseinu eta inprimaketa fitxategiak**, eta **A4 tamainako azken infografia PDF** formatuan.

Era berean, **taldearen lagin fitxategirako esteka** bat sortu behar da **3D/README.md** fitxategian, inprimatutako pieza guztien erregistroa gera dadin. [Probako adibidea ikusi](muestras/catalogo.md)

Taldeak erronka osatzen duenean, **Pull Request** bat egingo da klaseko errepositoriora irakasleak **berrikusi eta onartu** dezan.

**Git-eko fluxua:**

1. Klaseko errepositorioaren **Fork**a.
2. Adar berri bat sortu.
3. **Commit** txikiak, mezu argiekin.
4. **Pull Request**a klaseko errepositoriora.
5. Irakaslearen **berrikuspena eta onarpena**.

## Azkarreko egiaztapen-zerrenda (zuzenketarako)

* [ ] **A4 infografia**: parametroak + QC + irudia/diagrama + A4n irakurgarri + esteka/QR?
* [ ] **guia.md**: urratsak + pantaila-argazkiak + parametroak + denborak + konponketak + estekak STL/GCODEra
* [ ] **Eredua**: STL + GCODE + iturburua (CAD/SCAD)
* [ ] **Repo/PR**: egitura, estekak, adarra, commitak, PR
