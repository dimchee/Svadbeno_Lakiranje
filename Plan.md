
## Lakiranje rama

Recimo da imamo kvadratni ram napravljen od drveta, i želimo da ga izlakiramo
providnim lakom tačno 10 puta (da bi bilo ravnomerno), a zbog sušenja
je lakiranje moguće obaviti jednom dnevno, a zbog lepljenja za podlogu na
kojoj stoji to je moguće uraditi samo sa jedne strane. Ako nije moguće obeležiti
strane, kako da izvedemo ovo.

## Operacije

- Šta su operacije?
- Šta su funkcije?
- Šta znači da je funkcija bijekcija?
- Primeri (okretanje rama, min brojeva, unija skupova...)
- Osobine operacija (asocijativnost, jedinica, postojanje inverza)
- Neki će reći da izlakiran, i neizlakiran ram nisu isto
(mi biramo šta je isto, odnosno šta znači =)

## Grupe

- Šta je grupa
- Šta je abelova grupa

### Na koliko načina možemo da rotiramo kocku?

Fiksiramo donju stranu kocke (njih ima 6) a
onda kocku možemo da okrećemo kao kvadrat (ima 4 načina),
dakle 6 * 4 = 24

## Izomorfizmi

- Šta znači da je nešto izomorfno
- Šta je permutacija
- Kejlijeva teorema o izomorfizmu grupa (dokaz? uzmu se λₐ := g ↦ a*g)

## Kocka je bačena

- Šta je reprezentacija grupe
- Grupa $S_4$ je izomorfna sa rotacijama kocke
- Ne postoji reprezentacija grupe $S_4$ pomoću 1 elementa


## Geometrijska začkoljica

- Kako se krećemo po prostoru
- Šta programeri misle da su vektori (liste brojeva, nema nikakve osobine)
- Šta fizičari misle da su vektori (geometrijski vektori, videćemo zašto ovo nije dobro)
- Kako se sabiraju i skaliraju vektori
- treba nam da važe neke osobine

## Prostranstva

- Šta je V, šta je $K$ (polje) i da je $(V, +)$ abelova grupa
- Definicija vektorskog prostora
- Notacija $a \vec u + b \vec v$
- Dokaz nekih od izloženih osobina

## Kombinacije

- Šta je linearna kombinacija
- Šta je lineal
- Skup vektora $M$ je potpun ako je $L(M) = V$
- Skup vektora $M$ je linearno nezavisan ako se linearnom kombinacijom različitih
vektora iz $M$ vektor $0$ može dobiti samo ako su svi skalari $0$
- Svaki potpun, linearno nezavisan skup vektora prostora $V$ ima isti broj elemenata,
i taj broj naziva se dimenzija prostora $V$, a ovaj skup se naziva bazni skup.
- Svaki vektor se na jedinstven način može prikazati kao linearna kombinacija
različitih vektora baznog skupa. (dakle izomorfizam sa $K^{dim V}$)

## Fibonačijevi nizovi
- Navesti ih da nađu bazu (i da vide da se svi dobijaju preko nje)

## Zvuk slike

- Želimo da postavimo zvučnike tako da loptica od stiropora između lebdi
(ili još bolje da se kreće i pravi sliku)

## Perspektiva

- Zvučnik proizvodi zvuk po nekoj funkciji $p(x, y, z, t)$,
gde je pritisak u tački $(x, y, z)$ u trenutku $t$ jednak vrednosti
te funkciji.

## Linearna preslikavanja

- Šta je linearno preslikavanje
- Zašto je skup svih linearnih preslikavanja vektorski prostor?

## Red or Blue

- Šta su matrice i zašto svako linearno preslikavanje
može da se predstavi preko jedne (za odabrane baze)
- Množenje matrica je isto što i kompozicija funkcija
- Linearne funkcionele, dualni prostor, možda prirodni izomorfizam sa drugim dualom

## Igrice

- Rotacije i izduživanja su linearne transformacije.
- Translacije 3D prostora su linearne transformacije 4D prostora.
- Projekcije 4D prostora na 2D ekran su linearne transformacije.

## Kvadratići

- Kako bi definisali sabiranje i množenje magičnih kvadrata?
- Da li su operacije zatvorene?
- Šta je specijalno kod ovog magičnog kvadrata?

## Svadba
- $S$ - skup svih načina sedenja
- $A_i$ - skup svih načina sedenja tako da je $i$-ti gost na predviđenom mestu
- $|S| = n!$ - broj svih permutacija
- $|A_i| = (n-1)!$ - broj permutacija ako fiksiramo $i$-tog
- $|A_i \cap A_j| = (n-2)!$ - broj permutacija ako fiksiramo $i$-tog i $j$-tog
- $|A_i_1 \cap A_i_2 \cap ... \cap A_i_k| = (n-k)!$ - broj permutacija ako fiksiramo njih $k$

## Formula uključenja-isključenja
- Posmatrajmo vektorski prostor svih funkcija $V := |\cup_{i=1} n A_i| \to R$, i uočimo
karakteristične funkcije $I_X(x) = (x \in X ? 1 : 0)$
- Neka je $l_a(f) := f(a)$ za $f \in V$
- $l := \sum_{a \in A} l_a$ je linearna funkcionela
- $l(I_X) ?= |X|$
- Neka je $J := I_{\cup A_i}$, posmatrajmo $\prod_{i=1} n (J - I_{A_i}) = 0$

## Svadba2

- Sada je jasno $D(n) = n! - |\cup A_i| = n!(1 - 1 + \frac 1 {2!} - \frac 1 {3!} +...)$
- Ima li neko ideju čemu je ovo jednako, hajde da računamo ovo (nagađaju posle svakog)
- veza ovog izraza i broja $e$ u nekom drugom predavanju!
