# **_TEMA 1_**

# 1. INTRODUCCIÓ A LA PROGRAMACIÓ

### Per què programar?
#### Programar és una forma de resoldre reptes quotidians a través d'instruccions sistemàtiques. Com els humans prenem decisions i seguim passos per aconseguir resultats (jugar un videojoc, cuinar, conduir), els ordinadors també necessiten instruccions, que es donen mitjançant un programa. Un programa consisteix en un conjunt d'instruccions que el processador executa per obtenir un resultat.

## 1.1. Orígens de la programació
#### Amb la constant evolució informàtica en general hem vist com el camp de la programació ha donat un gran salt en el darrers anys però, tot això no hauria estat possible sense la contribució d'un gran nombre de persones, com per exemple:
 - Joseph Marie Jacquard: francès conegut per automatitzar, l'anomenat teler de Jacquard.

 - Charles Babbage: creador de la màquina diferencial i la màquina analítica (basada en el teler de Jacquard).

 - Ada Lovelace: desenvolupadora de programes per a la màquina analítica de Baggage, considerada la primera programadora de la història.

## 1.2. Llenguatge de la programació
#### Les instruccions que conté un programa s’especifiquen mitjançant un llenguatge que l’ordinador pugui entendre.

    1. Codi Font: Fitxer que conté les instruccions del programa.
    2. Linker: Inserta funcions necessàries de llibreries i crea un arxiu executable.
    3. Llibreria: Col·lecció de codi predefinit per facilitar la programació.
#### Els llenguatges es classifiquen segons el seu nivell d'abstracció (alt o baix) i el tipus de traducció a llenguatge màquina (compilat o interpretat).

#### Els llenguatges compilats tradueixen tot el codi a un executable, mentre que els interpretats tradueixen instrucció per instrucció. Python seria un llenguatge d'alt nivell i de tipus compilat.
![compilat i interpretat](https://lh4.googleusercontent.com/2Vag5YX6N2Rs5QtNFd6Jd4iYy0prUOcjNq_fDC3kMHqj66qKjIGHMq_L8dhjA5Bv9TrDVCMKrp8IF0Cs-PcvH7rJ0kyz4s0iMxLBKalTfxpflSsHOgotCD_tPTQU6zVlKA=w1280)

## 1.3. Classificació dels llenguatges i paradigmes de programació
### 1. Generacions dels llenguatges de programació
  - Primera generació: llenguatges de baix nivell/màquina. És màquina-dependent, necessiten ser interpretades per un ordinador, les sentències del programa s'escriuen en codi binari (0/1).
  - Segona generació: llenguatges d’assemblador (programa que converteix instruccions d'assemblador a llenguatge màquina). 
  - Tercera generació: llenguatges de alt nivell/procedimental on es fan ús de procediments/passos de manera lògica, seguint un ordre.
  - Quarta generació: llenguatges de propòsit indefinit, alt nivell d’abstracció en la programació, que permet desenvolupar aplicacions sofisticades en un espai curt de temps.
  - Cinquena generació: llenguatges basats en el concepte d'intel·ligència artificial.
### 2. Paradigmes
#### Seria la forma estructural i organitzada de les tasques en un programa. Cada paradigma te les seves distincions:

 - Programació Imperativa: basada en donar instruccions a l'ordinador mitjançant algoritmes. Llenguatges com C, BASIC i Pascal en són exemples.

 - Programació Orientada a Objectes: es fonamenta en el paradigma imperatiu, utilitzant “objectes” que combinen variables i funcions. Java i Smalltalk per exemple.

 - Programació Dirigida per Esdeveniments: es basa en l'execució del programa en funció d'esdeveniments que ocorren al sistema, com a Visual Basic.

 - Programació Declarativa: descriu el problema mitjançant propietats i regles, sense especificar el procés per resoldre'l. Llenguatges com Prolog, exemple.

 - Programació Multiparadigma: combina dos o més paradigmes en un sol programa, i permetent triar l'enfocament més adequat. Exemples com Lisp, Python i C++.

## 1.4. Els llenguatges de programació més populars
#### A l'hora d'escollir un llenguatge de programació s'ha de tenir en compte certs factors com:
 - El propòsit del programa
 - L'entorn d’execució
 - La versatilitat del llenguatge
 - Les tendències del mercat

#### Llista dels 10 llenguatges de programació més utilitzats (setembre 2024).
![top10_llenguatges](https://lh5.googleusercontent.com/YOcrzW9hETIn4WHdWXZvvR1e6chKeH-0rJJVPmpindZkwP2_eqDx9d4W91ilI3rRpSmb1YFQA6_hFFnA29ZKz2XhTAt3NtaFvQlCS48FT-Jlhwjx4P9wRvh-P3PDPPqHtg=w1280)


# 2. DISSENY D'ALGORISMES
#### En aquest segon apartat es veuran les etapes que s'han de seguir a l'hora de dissenyar un programa:
    1. Anàlisi: estudi del problema a resoldre.

    2. Disseny: es defineix la manera de resoldre l'algorisme, indicant els passos.

    3. Programació: s'implementen les instruccions l’algorisme en un llenguatge de programació d’alt nivell.

    4. Compilació: el codi d’alt nivell es tradueix de manera que l’ordinador pugui executar el programa.

    5. Execució i proves: s’executa el codi amb diferents valors d’entrada per provar que funciona en qualsevol cas.

## 2.1. Anàlisi
#### Estudiarem detalladament el problema que volem resoldre, incloent-hi la solució requerida, les dades disponibles i possibles errors o excepcions. En aquesta fase busquem una comprensió sencera del problema.

#### Un bon algorisme ha de ser:

 - Precís: defineix clarament cada pas a seguir.
 - Ben definit: proporcionar la mateixa sortida per les mateixes entrades.
 - Finit: s'ha d'acabar.
 - Robust: gestionar totes les entrades amb respostes clares.
 - Transportable: funcionar en diferents maquinaris i programari (hardware i software).

#### Abans de proporcionar una solució ens hem de fer una serie de preguntes a resoldre:
  - Quina és la solució demanada? 
  - De quina informació disposem?
  - Quines operacions cal realitzar?
  - Les operacions responen a la pregunta?
  - Hi ha risc d'errors durant a l'hora d'operar?

### 2.1.1 Les dades 
#### Una dada és una representació simbòlica (numèrica, alfabètica, etc.) d'una característica d'alguna cosa. Per si sola, no té valor semàntic, però quan es processa, pot ser útil per a càlculs o presa de decisions. Els programes informàtics necessiten dades d'entrada per executar-se, analitzar-les i convertir-les en noves dades de sortida.

#### Les dades no són totes iguals; es classifiquen en diferents tipus:

 - Simples:
    - numèriques:
        - Enter: valors sense decimals, positius o negatius.
        - Real: valors amb decimals, positius o negatius.
    - no numèriques:
      - Booleà: valors lògics (cert o fals). 
      - Caràcter / cadena de caràcters: unitats de text.
      - Estructurades:
- Estructurades
    - Internes:
       - Estàtiques: registres, vectors, taules.
       - Dinàmiques: llistes, cues, piles, arbres.
    - Externes:
       - Fitxers.
       - Bases de dades.

### 2.1.2 Les expressions
#### Una expressió és la combinació d'operands i operacions de manera que junts fan una acció.

#### Els operands es classifiquen en:

 - Variables: dades que poden canviar durant l'execució del programa.
 - Constants: valors que només es poden llegir i no modificar.
 - 
#### Els operadors que permeten realitzar accions sobre els operands inclouen:

 - Assignació: x = y
 - Aritmètics:
   - Addició: x = x + y
   - Sostracció: x = x - y
   - Multiplicació: x = x * y
   - Divisió: x = x / y
   - Mòdul: x = x % y
   - Increment: ++
   - Decreixement: --
   - Potenciació: **
 - Comparació:
   - "==" (igual)
   - "!=" (diferent)
   - "<" (menor que)
   - ">" (més gran que)
   - "<="(menor o igual que)
   - ">="(més gran o igual que)

## 2.2. Disseny
#### En aquesta etapa es descriuen de manera detallada tots aquells processos/passos que el progrmaa ha de ser per resoldre algun problema.
### 2.2.1. Especificació
#### Com hem dit anteriorment es necessari descomposar el problema que volem resoldre en problemes més petits per després decriure el passos que s'han de seguir per trobar la solució. Existeixen diverses maneres de representar aquests passos, tals com:
 - Pseudocodi
 - Diagrames de flux
 - Diagrames de Nassi-Shneiderman
### 2.2.2. Pseudocodi
#### Es presenta com llistats/textos que compten amb un inici i un final i van encapsulant altres instruccions. En les primeres linies del pseudocodi es declaren les variables i constants que necessita l'algorisme i en el cos del programa totes aquelles instruccions a executar. Compte perquè es podràn fer ús de estructures condicionals on les instruccions només es realizen si es cumpleixen certes condicions, també poden apareixer els bucles que repeteixen un process sempre i quan es compleixi la condició.
![Exemple pseudocodi](https://huberthalcantara.wordpress.com/wp-content/uploads/2012/03/image12.pngg)
 - Condicionals:
   - if ... then (si es compleix la condició fes...)
   - else ... (sino es compleix el "if" fes...)
 - Bucles:
   - while...do (mentre es compleixi la condició fes)
   - Do...while (fer la instrucció i després comprobar que es compleixi la condició per a tornar a actuar)
   - For...to... (repetir desde el valor incial fins al valor final una serie d'instruccions)

### 2.2.3. Diagrames de flux
#### Són representacions visuals dels processos es fa per mitjà de diferents formes geomètriques per representar les operacions a seguir i es conecten amb fletxes.
![formes geometriques](https://lh6.googleusercontent.com/6Um0yb9HwSgEgvraAioG3xnoeYGSc_7xQRZF440Sytkfb0nCtHQ0FeZpPVri6Zo6nf8jGUiyy6lz5itJ7S5r66RjXYNnCPdutlr2j5XlT2aHEa-IfZM84caEi7dR9R1Pwg=w1280)
#### Exemple:
![exemple de diagrama](https://lh4.googleusercontent.com/Nu2fsxjbZczi0HJpMYqItp4tJGpdyzmbf9U3N30BRLsuUJ3VfnmW6jCrDRJiEHsst1UJAqU83ckN9KapMBOiF46mcfDc7p7ymAa1fV4gK9kN6yrhuOtFzyhqZlFdHfh3og=w1280)
### 2.2.3 Diagrames de Nassi-Shneiderman
#### Són una forma de representació gràfica d'algorismes que utilitza una estructura de blocs. Representa cada instrucció com a una caixa que es pot combinar.
 - Blocs rectangulars: representen instruccions o operacions.
 - Blocs dividits: indiquen estructures condicionals o bucles.

![exemple diagrama Nassi](https://image.jimcdn.com/app/cms/image/transf/none/path/sab24d320592e0f50/image/i16d3e84658e340de/version/1662842967/image.png)

### 2.2.5 Jocs de proves
#### En dissenyar un algorisme, és essencial realitzar proves per avaluar la seva validesa. Els jocs de proves documenten els casos analitzats i els resultats obtinguts, ajudant a corregir i millorar els programes. Detectar errors al principi del desenvolupament és crucial, ja que solucionar-los més tard pot requerir molt més esforç. Per tant, és una bona pràctica elaborar el joc de proves abans d'implementar l'algorisme en un llenguatge d'alt nivell.