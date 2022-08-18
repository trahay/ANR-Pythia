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
portable. [code source](https://gitlab.com/eztrace/eztrace)

- **Développement de l’outil d’analyse de trace EasyTraceAnalyzer** :
un outil extensible permettant l’implémentation d’analyses variés sur
des traces dans des formats divers.[code
source](https://gitlab.com/parallel-and-distributed-systems/easytraceanalyzer)


## Documents utiles

Rédiger un projet ANR peut être complèxe, particulièrement pour un
jeune chercheur. Si cela peut aider la génération suivante de jeunes
chercheurs, je mets à disposition les documents que j'ai soumis à
l'ANR et qui m'ont permis de financer ce projet. N'hésitez pas à vous
en inspirer si besoin.

- [Soumission du document court (phase 1)](ANR_proposal/phase1/)
- [Soumission du document long (phase 2)](ANR_proposal/phase2/)
- [Rapport intermédiaire)](ANR_reports/ANR_Pythia_rapport_intermediaire_a_18_mois.pdf)
