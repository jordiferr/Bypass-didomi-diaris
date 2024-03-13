# Bypass-didomi-diaris

Didomi és un paywall utilitzat pel diari Ara i LaVanguardia.<br />
Aquests scripts són una primera forma de poder fer un bypass i poder llegir els articles publicats sense necessitat de registrar-nos.<br />
Articles que estàn publicats *dins el codi font HTML que t'entreguen a TU, al TEU ordinador*, a la teva propietat. Només estàs desbrossant un garbuix que et causa molèsties als ulls.

## Com utilitzar-ho

### Pas 1

Has de saber utilitzar la línia de comandes.<br />
Necessitaràs:
- Curl
- Vim o NeoVim (res d'altres editors com **ed** o com *nano*. Ni un sistema operatiu al que li manca un bon editor de text.)

### Pas 2

Copia la URL que vols llegir.<br />
Obre un terminal i escrius <code>curl -s URL >> fitxer_a_guardar</code>

### Pas 3

Després clonar el repositori a una carpeta del TEU sistema, faràs:
1. <code>vim fitxer_a_guardar</code>
2. en mode comanda escrius <code>:source ara_articles.vimscript</code>

### Pas 4

Acabes TU de netejar una mica el que queda amb les comandes <code>dw</code>, <code>D</code>, etc...<br />
<br />
Bona lectura
