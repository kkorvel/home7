# README #

See on seitsmenda kodutöö failide hoidla, mida saab kasutada ainult
lugemiseks.
Töötamiseks looge endale isiklik repositoorium, näiteks privaatne 'fork' bitbucket serverisse, millest saate luua klooni oma arvutisse.

## Näidete kasutamine käsurealt ##
#### Kompileerimine: ####

```
#!bash

javac -cp src src/Puzzle.java
```

#### Käivitamine: ####

```
#!bash

java -cp src Puzzle
```


### Testide kasutamine ###
#### Testi kompileerimine: ####

```
#!bash

javac -encoding utf8 -cp 'src:test:test/junit-4.12.jar:test/hamcrest-core-1.3.jar' test/PuzzleTest.java

```
Sama Windows aknas (koolonite asemel peavad olema semikoolonid):

```
#!bash

javac -encoding utf8 -cp 'src;test;test/junit-4.12.jar;test/hamcrest-core-1.3.jar' test/PuzzleTest.java


```

#### Testi käivitamine: ####

```
#!bash

java -cp 'src:test:test/junit-4.12.jar:test/hamcrest-core-1.3.jar' org.junit.runner.JUnitCore PuzzleTest
```

Sama Windows aknas (koolonite asemel semikoolonid):

```
#!bash

java -cp 'src;test;test/junit-4.12.jar;test/hamcrest-core-1.3.jar' org.junit.runner.JUnitCore PuzzleTest
```
