# Apollo-11
[![NASA][1]][2]

:crossed_flags:
[Bahasa Indonesia][ID],
[Català][CA],
[Deutsch][DE],
[English][EN],
[Español][ES],
**Français**,
[Italiano][IT],
[Polski][PL],
[Português][PT_BR],
[Русский][RU],
[Türkçe][TR],
[Română][RO],
[العربية][AR],
[हिंदी][HI_IN],
[正體中文][ZH_TW],
[简体中文][ZH_CN],
[한국어][KO_KR]

[AR]:README.ar.md
[ID]:README.id.md
[CA]:README.ca.md
[DE]:README.de.md
[EN]:README.md
[ES]:README.es.md
[IT]:README.it.md
[PL]:README.pl.md
[FR]:README.fr.md
[PT_BR]:README.pt_br.md
[TR]:README.tr.md
[ZH_TW]:README.zh_tw.md
[ZH_CN]:README.zh_cn.md
[KO_KR]:README.ko_kr.md
[HI_IN]:README.hi_in.md
[RU]:README.ru.md
[RO]:README.ro.md

Code source original de l'ordinateur de guidage Apollo 11 (AGC) pour le module de commande (Comanche055) et le module lunaire (Luminary099). Numérisé par les gens du [Virtual AGC][3] et du [MIT Museum][4]. Le but est d'être un repo pour le code source original d'Apollo 11. En tant que tel, les PR sont les bienvenues pour tous les problèmes identifiés entre les transcriptions dans ce référentiel et les scans source originaux pour [Luminary 099][5] et [Comanche 055][6], ainsi que pour tous les fichiers que j'ai pu manquer.

## Contribuer
Merci de lire [CONTRIBUTING.md][7] avant d'ouvrir une pull request.

## Compilation
Si vous êtes intéressés par la compilation du code source original visitez [Virtual AGC][8].

## Attribution

&nbsp;         | &nbsp;
:------------- | :-----
Copyright      | Domaine public
Comanche055    | Partie du code source de Colossus 2A, le module de commande (CM) Ordinateur embarqué de navigation (AGC), pour Apollo 11.<br>`Assemble revision 055 of AGC program Comanche by NASA`<br>`2021113-051. 10:28 APR. 1, 1969`
Luminary099    | Partie du code source de Luminary 1A, le module de lunaire (LM) Ordinateur embarqué de navigation (AGC), pour Apollo 11.<br>`Assemble revision 001 of AGC program LYM99 by NASA`<br>`2021112-061. 16:27 JUL. 14, 1969`
Assembleur      | yaYUL
Contact        | Ron Burkey <info@sandroid.org>
Site internet  | www.ibiblio.org/apollo
Numérisation   | Ce code source a été transcrit ou autrement adapté à partir de données numérisées des images d'une copie papier du Musée du MIT. La numérisation a été effectuée par Paul Fjeld, et organisé par Deborah Douglas du Musée. Un grand merci à eux deux.

### Contrat et Approbations
*Dérivé de [CONTRACT_AND_APPROVALS.agc]*

```plain
CE PROGRAMME DE L'AGC SERA ÉGALEMENT DÉSIGNÉ SOUS LE NOM DE :
    COLOSSUS 2A

CE PROGRAMME EST DESTINÉ À ÊTRE UTILISÉ EN CM COMME INDIQUÉ
DANS LE RAPPORT R-577.  CE PROGRAMME A ÉTÉ PRÉPARÉ DANS LE CADRE
DU DSRDSR PROJET 55-23870, PARRAINÉ PAR L'ENGIN SPATIAL HABITÉ
CENTRE NATIONAL DE L'AÉRONAUTIQUE ET DE L'ADMINISTRATION SPATIALE
PAR LE BIAIS DU CONTRAT NAS 9-4065 AVEC LE LABORATOIRE
D'INSTRUMENTATION, INSTITUT DE TECHNOLOGIE DU MASSACHUSETTS,
CAMBRIDGE, MASS.
```

Soumis par            | Rôle | Date
:-------------------- | :--- | :---
Margaret H. Hamilton  | Chef de la programmation Colossus<br>Programme de guidage et de navigation Apollo | 28 Mar 69

Approuvé par       | Rôle | Date
:----------------- | :--- | :---
Daniel J. Lickly   | Directeur, Développement des programmes de mission<br>Programme de guidage et de navigation Apollo | 28 Mar 69
Fred H. Martin     | Chef de projet Colossus<br>Programme de guidage et de navigation Apollo | 28 Mar 69
Norman E. Sears    | Directeur, Développement de la mission<br>Programme de guidage et de navigation Apollo | 28 Mar 69
Richard H. Battin  | Directeur, Développement de la mission<br>Programme de guidage et de navigation Apollo | 28 Mar 69
David G. Hoag      | Directeur<br>Programme de guidage et de navigation Apollo | 28 Mar 69
Ralph R. Ragan     | Directeur adjoint<br>Laboratoire d'instrumentation | 28 Mar 69

[CONTRACT_AND_APPROVALS.agc]:https://github.com/chrislgarry/Apollo-11/blob/master/Comanche055/CONTRACT_AND_APPROVALS.agc
[1]:https://cdn.rawgit.com/aleen42/badges/c9246f74/src/nasa.svg
[2]:https://www.nasa.gov/mission_pages/apollo/missions/apollo11.html
[3]:http://www.ibiblio.org/apollo/
[4]:http://web.mit.edu/museum/
[5]:http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/
[6]:http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/
[7]:https://github.com/chrislgarry/Apollo-11/blob/master/CONTRIBUTING.md
[8]:https://github.com/rburkey2005/virtualagc
