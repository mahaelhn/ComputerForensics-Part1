# ComputerForensics-Part1


Une analyse forensique fait généralement suite à un incident : par exemple un serveur a été compromis et l’on souhaite déterminer les actions qui ont été effectuées sur les machines ainsi de collecter des preuves afin de pouvoir porter plainte. 

Il existe encore de nombreux domaines où l’on utilise l’analyse forensique :
*-Analyse de malwares (surveillance du poste afin de déterminer les actions d’un
malware)
*- Récupération de preuves en vue d’une plainte (intrusion, pédocriminalité, vol de
données, etc.)
*- Test d’intrusion (récupération d’informations sensibles)
*- Récupération de données après sinistre

Il existe 3 types d’analyses forensique distinctes :
- L’analyse à froid (le dead forensics) : Elle consiste à analyser un système éteint.
Dans ce cas l’ensemble des données du système sera copié et analysé
ultérieurement. C’est l’approche la plus complète mais qui nécessite le plus de
temps.
- L’analyse à chaud (le live forensics) : Cette analyse consiste à analyser l’état d’un
système à un moment T. Dans ce cas, l’enquêteur récupère des informations issues
de la mémoire vive.
- L’analyse en temps réel : Consiste à capturer et à analyser le trafic réseau.
Au cours de ce document, nous ne traiterons que de l’analyse à chaud (live forensics).

Dans ComputerForensics-Part1, nous avons focalisé sur l'analyse forensique à froid. (voir le fichier)
