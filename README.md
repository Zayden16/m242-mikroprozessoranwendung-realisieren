# M242: Mikroprozessoranwendung realisieren (Block I)
## Prozessor:
Ein Prozessor ist eine Zusammenstellung von Transistoren, welche alle Rechenvorgänge mit Hilfe vom Binärsystem löst. Befehle werden in Maschinensprache an den Prozessor weiter geleitet. 

## Mikroprozessor:
Ein Mikroprozessor ist ein Prozessor in sehr kleinem Masstab, bei dem alle Bausteine des Prozessors auf einem Mikrochip vereinigt sind

## CPU:
Central Processing Unit, Rechenwerk + Steuerwerk = CPU
Hauptkomponente:

    -Steuerwerk
    -Rechenwerk
    -Register

Jeder Prozessor hat folgende Register:

    -Akkumulator
    -Program Status Word, Flag-Register
    -Program Counter, Befehlszähler
    -Registerblock

## Minimalsystem:
Ein Minimalsystem besteht aus folgende Teile:

    -Adressbus
    -CPU
    -ROM
    -RAM
    -I/O
    -Databus
    -Steuerbus 

## Von-Neumann-Architektur:
 Ist ein Referenzmodell für Computer, wonach ein gemeinsamer Speicher sowohl Computerprogrammbefehle als auch Daten hat.
 Sie besteht aus:

    -Rechenwerk
    -Steuerwerk
    -Speicherwerk
    -I/O

Die 3 Phasen der VNA sind:

    -FETCH:
    Laden der Befehle, Adresse des nächsten Befehls ausgeben, Befehlsbyte vom Speicher ins Befehlsregister holen

    -DECODE:
    Decodierung der Befehle, entschlüsseln des binären Datenwortes.

    -EXECUTE:
    Ausführen der innerhalb des Befehls codierten Aktion.

## Havard Architektur:
Ist ein Schaltungkonzept, bei dem der Befehlsspeicher logisch und physisch vom Datenspeicher getrennt ist


## Steuerbus:
Der Steuerbus ist zuständig für die zeitliche Ablaufsteuerung innerhalb der Zentraleinheit.

## Addressbus:
>TODO


## Datenbus:
Ist für den Transport der Daten zuständig.

## Reset:
Die Reset Leitung dient dazu den Programmcounter wieder zurück zu stellen. Dies ermöglicht ein manuelles Reset z.Bs. nach einem Programmabsturz.

## Steuerwerk:
Ist eins Leitwerk, welches den Ablauf der Befehlsverarbeitung steuert, lädt Befehle, decodiert und interpretiert diese ggf.. Zugleich gibt es Steuersignale an andere Funktionseineiten, z.Bs. das Rechenwerk. 

Ein Steuerwerk besteht aus:

    -Befehlszähler
    -Befehlsregister
    -Befehlsdecoder

## RAM:
Random Access Memory, wird für die temporäre Speicherung benutzt
Es gibt zwei arten von RAM:

    -Statisches RAM: Schnell
    -Dynamisches RAM: Kleine Speichergrösse

## ROM:
Read Only Memory, ist ein Datenspeicher, der nur lesend zugegriffen werden kann,der nicht flüchtig ist.

    -EEPROM: Electronically Erasable Programmable Read Only Memory
    -EPROM: Erasable Programmble Read Only Memory
    -PROM: Programmable Read Only Memory

## ALU:
Arithmetisch-logische Einheit, zuständig für:

    -Aritmetische Operatoren
    -Bitmanipulationen
    -Schiebeoperationen

    ALU hat folgende bestandteile:
        -Akkumulator
            -Multiplikationsregister (MR)
			-Link Register (LR) (addition)

        -Memory Buffer Register

## Status Register:
Informiert überden Ausgang einer Rechnung.

