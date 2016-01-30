# Dokumentacja projektu Warcaby
#### Przedmiot: Inżynieria oprogramowania, Projekt zespołowy.
##### Autorzy: Grzegorz Mucha, Tomasz Myszak, Borys Sola.
###### Version: 0.1
---
#### Spis treści:
  - Wstęp
  - Diagramy UML
  - Zasady gry

---
### Wstęp

Celem naszej pracy było stworzenie projektu symulującego **grę w warcaby**. W naszej aplikacji można prowadzić rozgrywki między **dwoma graczami (PVP)** lub **gracz przeciwko "komputerowi" (PVC)**. W programie możliwe jest wprowadzanie dowolnej ilości graczy, prowadzona jest również historia rozgrywek.



Program napisany został w języku **Java**.
Edytory: **Eclipse** oraz **NetBeans 8.1** 

<img width="510" alt="2016-01-30 3" src="https://cloud.githubusercontent.com/assets/13695822/12696450/66f72152-c76b-11e5-82cf-1906c9e1b599.png">

Dostęp do projektu [Warcaby].

---
### Diagramy UML
###### Diagram czynności gra
![diagramczynnosci_gra](https://cloud.githubusercontent.com/assets/13695822/12696451/671b25f2-c76b-11e5-8ad7-a6cd48a57da2.jpg)
###### Diagram czynności tura
![diagramczynnosci_tura](https://cloud.githubusercontent.com/assets/13695822/12696453/6730411c-c76b-11e5-8c25-5e9b4b25433b.jpg)
###### Diagram czynności wybierz tryb gry
![diagramczynnosci_wybierztrybgry](https://cloud.githubusercontent.com/assets/13695822/12696452/67302f2e-c76b-11e5-9763-09c0e85c26e7.jpg)
###### Diagram klas
![diagramklas](https://cloud.githubusercontent.com/assets/13695822/12696455/67325d80-c76b-11e5-8a50-9e4cc43db683.jpg)
###### Diagram sekwencji rozgrywka
![diagramsekwencji_rozgrywka](https://cloud.githubusercontent.com/assets/13695822/12696454/67315854-c76b-11e5-9a0c-5eb4bb7cad23.jpg)
###### Diagram sekwencji wybór trybu gry
![diagramsekwencji_wybortrybugry](https://cloud.githubusercontent.com/assets/13695822/12696456/673711b8-c76b-11e5-9a71-57445e615b6d.jpg)
###### Diagram sekwencji tura
![diagramsekwencjitura](https://cloud.githubusercontent.com/assets/13695822/12696457/67399442-c76b-11e5-8666-7a4c0045a8bd.jpg)
###### Diagram stanu gry
![diagramstanu_gra](https://cloud.githubusercontent.com/assets/13695822/12696459/675080da-c76b-11e5-9d15-0b023b600725.jpg)
###### Diagram stan rogrywki
![diagramstanu_rozgrywka](https://cloud.githubusercontent.com/assets/13695822/12696458/6750af7e-c76b-11e5-912c-e42fb388802d.jpg)

---
### Zasady gry:
>Jako pierwszy ruch wykonuje grajacy pionami niebieskimi, po czym gracze wykonuja na zmiane kolejne ruchy.

>Celem gry jest zbicie wszystkich pionow przeciwnika albo zablokowanie wszystkich, ktore pozostajo na planszy, pozbawiajac przeciwnika mozliwosci wykonania ruchu.

>Piony moga poruszac sie o jedno pole do przodu po przekatnej (na ukos) na wolne pola.

>Bicie pionem nastepuje przez przeskoczenie sasiedniego pionu (lub damki) przeciwnika na pole znajdujace sie tuz za nim po przekatnej (pole to musi byc wolne). Zbite piony sa usuwane z planszy po zakonczeniu ruchu.

>Piony moga bic zarowno do przodu, jak i do tylu.

>W jednym ruchu wolno wykonac wiecej niz jedno bicie tym samym pionem, przeskakujac przez kolejne piony (damki) przeciwnika.

>Bicia sa obowiazkowe.

>Pion, ktory dojdzie do ostatniego rzedu planszy, staje sie damka, przy czym jezli znajdzie sie tam w wyniku bicia i bedzie mogl wykonac kolejne bicie (do tylu), to bedzie musial je wykonac i nie staje sie wtedy damka.

>Kiedy pion staje sie damka, kolej ruchu przypada dla przeciwnika.

>Damki moga poruszac sie w jednym ruchu o jedno pole do przodu lub do tylu po przekatnej.

>Kiedy istnieje kilka mozliwych bic, gracz musi wykonac maksymalne (tzn. takie, w ktorym zbije najwieksza liczbe pionow lub damek przeciwnika).

>Podczas bicia nie mozna przeskakiwac wiecej niz jeden raz przez ten sam pion (damka).

---

[Warcaby]: <https://github.com/comop/warcaby>



