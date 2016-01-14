#Característiques dels llenguatges més difosos.
##•Llenguatge estructurat
####_Claredat_ 

Hi haurà d’haver prou informació al codi per tal que el programa pugui ser entès i verificat: comentaris, noms de variables comprensibles i procediments entenedors... Tot programa estructurat pot ser llegit des del principi a la fi sense interrupcions en la seqüència normal de lectura. 

####_Teorema de l’estructura_ 

Demostra que tot programa es pot escriure utilitzant únicament les tres estructures bàsiques de control: 
• **Seqüència**: instruccions executades successivament, una darrere l’altra. Un exemple de l’estructura bàsica de seqüència, on primer s’executarà la sentència A i, posteriorment, la B. 

• **Selecció**: la instrucció condicional amb doble alternativa, de la forma “si condició, llavors SentènciaA, sinó SentènciaB”.

• **Iteració**: el bucle condicional “mentre condició, fes SentènciaA”, que executa les instruccions repetidament mentre la condició es compleixi.

####_**Disseny descendent**_ 

El disseny descendent és una tècnica que es basa en el concepte de divideix i venceràs ("Divide and conquer") per tal de resoldre un problema en l’àmbit de la programació. Es tracta de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un nivell més abstracte i finalitzant en un nivell de detall. 

##•Llenguatge orientat a objectes

####_Abstracció_

És el procés en el qual se separen les propietats més importants d’un objecte de les que no ho són. És a dir, per mitjà de l’abstracció es defineixen les característiques essencials d’un objecte del món real, els atributs i comportaments que el defineixen com a tal, per després modelar-lo en un objecte de programari. En el procés d’abstracció no ha de ser preocupant la implementació de cada mètode o atribut, només cal definir-los. En la tecnologia orientada a objectes l’eina principal per suportar l’abstracció és la classe. Es pot definir una classe com una descripció genèrica d’un grup d’objectes que comparteixen característiques comunes, les quals són especificades en els seus atributs i comportaments.

####_Encapsulació_
Permet als objectes triar quina informació és publicada i quina informació és amagada a la resta dels objectes. Per això els objectes solen presentar els seus mètodes com a interfícies públiques i els seus atributs com a dades privades o protegides, essent inaccessibles des d’altres objectes. Les característiques que es poden atorgar són:<br>

**• Públic:** qualsevol classe pot accedir a qualsevol atribut o mètode declarat com a públic i utilitzar-lo.<br>
**• Protegit:** qualsevol classe heretada pot accedir a qualsevol atribut o mètode declarat com a protegit a la classe mare i utilitzar-lo.<br>
**• Privat:** cap classe no pot accedir a un atribut o mètode declarat com a privat i utilitzar-lo.

####_Modularitat_

Permet poder modificar les característiques de cada una de les classes que defineixen un objecte, de forma independent de la resta de classes en l’aplicació. En altres paraules, si una aplicació es pot dividir en mòduls separats, normalment classes, i aquests mòduls es poden compilar i modificar sense afectar els altres, aleshores aquesta aplicació ha estat implementada en un llenguatge de programació quesuporta la modularitat.
