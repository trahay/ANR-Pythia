# ANR-Pythia

Le projet Pythia est un projet de recherche financé par l'ANR.

- [Projet ANR Pythia](https://anr.fr/Projet-ANR-18-CE25-0005)
- Programme: ANR JCJC 2018
- Coordinateur: [François Trahay](https://trahay.wp.imtbs-tsp.eu/) (Télécom SudParis, équipe [PDS](https://www.inf.telecom-sudparis.eu/pds/))
- Partenaire: [Télécom SudParis](https://www.telecom-sudparis.eu/)
- Budget: 184 056 euros
- Dates du projet: 02/2019 - 08/2022

## Résumé
Les supports d'exécution prennent des décisions critiques pour les performances
d'applications parallèles. Malheureusement, ces décisions ne peuvent se baser que sur des
heuristiques prenant en compte l'état actuel de l'application, et estimant son comportement
probable dans le futur. Par conséquent, les supports d'exécution prennent parfois des
décisions qui détériorent les performances au lieu de les améliorer.

Pythia vise à fournir aux supports d'exécution des moyens de prédire le futur de manière
précise. Pour cela, Pythia se base sur la nature déterministe de la plupart des applications
parallèles : généralement, un programme aura le même comportement d'une exécution à
l'autre. Dans le cadre de Pythia, nous concevrons une chaîne d'outils qui analyse l'exécution
d'un programme afin de fournir aux supports d'exécution des indications lors d'exécutions
futures du même programme. Grâce à des indications, un support d'exécution pourrait
prendre des décisions en se basant à la fois sur l'état actuel de l'application, et sur le
comportement futur du programme.

## Résultats marquants

- **Développement d’EZTrace 2.0** : une refonte du code source a
permis de simplifier sa maintenance et de rendre le logiciel plus
portable. [[code source](https://gitlab.com/eztrace/eztrace)]

- **Développement de l’outil d’analyse de trace EasyTraceAnalyzer** :
un outil extensible permettant l’implémentation d’analyses variés sur
des traces dans des formats divers. [[code
source](https://gitlab.com/parallel-and-distributed-systems/easytraceanalyzer)]

- **Développement de la librarie Pythia** qui fournit un service de collecte de trace et de prédictions pour les supports d’exécution
[[code source](https://github.com/libPythia/pythia)] [[publication](https://hal.archives-ouvertes.fr/hal-03750441/document)]

## Publications


### International conferences or journals with peer review
Alexis Colin, François Trahay, Denis Conan. *PYTHIA: an oracle to guide runtime system decisions.* In IEEE Cluster, Heidelberg, Germany, 2022. 
[[pdf](https://hal.archives-ouvertes.fr/hal-03750441/document)] [[bib](https://hal.archives-ouvertes.fr/hal-03750441v1/bibtex)]

Thao Truong, François Trahay, Jens Domke, Aleksandr Drozd, Emil Vatai, Jianwei Liao​, Mohamed Wahib, Balazs Gerofi. *Why Globally Re-shuffle? Revisiting Data Shuffling in Large Scale Deep Learning.*
In IPDPS 2022. [[pdf](https://hal.archives-ouvertes.fr/hal-03599740/document)] [[bib](https://hal.archives-ouvertes.fr/hal-03599740v1/bibtex)]

Naas, M. I., Trahay, F., Colin, A., Olivier, P., Rubini, S., Singhoff, F., & Boukhobza, J. *EZIOTracer: unifying kernel and user space I/O tracing for data-intensive applications.*
In SIGOPS Operating Systems Review. 55, 1 (July 2021), 88–98. [[pdf](https://hal.archives-ouvertes.fr/hal-03215663/document)] [[bib](https://dl.acm.org/doi/abs/10.1145/3469379.3469391)]

Alexis Lescouet, Élisabeth Brunet, François Trahay, and Gaël Thomas. *Transparent Overlapping of Blocking Communication in MPI Applications.* in HPCC 2020.	[[pdf](https://hal.archives-ouvertes.fr/hal-03007204/document)] [[bib](https://hal.archives-ouvertes.fr/hal-03007204v1/bibtex)]

Mohamed Said Mosli Bouksiaa, François Trahay, Alexis Lescouet, Gauthier Voron, Remi Dulong, Amina Guermouche, Elisabeth Brunet, Gaël Thomas. *Using differential execution analysis to identify thread interference.* In IEEE Transactions on Parallel and Distributed Systems (TPDS). 2019. [[pdf](https://hal.archives-ouvertes.fr/hal-02179717/document)] [[bib](https://hal.archives-ouvertes.fr/hal-02179717v1/bibtex)]

### National conferences with peer review

Alexis Colin, François Trahay, Denis Conan. *PYTHIA : un oracle pour guider les décisions des runtimes.* In Compas'2022.
[[pdf](https://hal.archives-ouvertes.fr/hal-03754168/document)] [[bib](https://hal.archives-ouvertes.fr/hal-03754168v1/bibtex)]

Alexis Colin, François Trahay. *Factorisation de traces d’exécutions de programmes pour l’analyse et la prédiction.* In Compas'2020.


## Documents utiles

Rédiger un projet ANR peut être complèxe, particulièrement pour un
jeune chercheur. Si cela peut aider la génération suivante de jeunes
chercheurs, je mets à disposition les documents que j'ai soumis à
l'ANR et qui m'ont permis de financer ce projet. N'hésitez pas à vous
en inspirer si besoin.

- [Soumission du document court (phase 1)](ANR_proposal/phase1/)
- [Soumission du document long (phase 2)](ANR_proposal/phase2/)
- [Rapport intermédiaire](ANR_reports/ANR_Pythia_rapport_intermediaire_a_18_mois.pdf)
