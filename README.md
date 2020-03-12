# Projets tutorés DUBii

- [Logigramme de vos analyses](#logigramme-de-vos-analyses)
- [Plan de gestion des données](#plan-de-gestion-des-données)
- [Description de vos métadonnées](#description-de-vos-métadonnées)


## Logigramme de vos analyses

Nous demandons à chacun de dessiner un organigramme conceptuel (logigramme, *flowchart*) qui exposera la logique de son workflow d'analyse, en utilisant l'outil [draw.io](https://draw.io/). 

Votre logigramme pourra être complété au fil des cours, en ajoutant les différentes étapes et outils que vous envisagez d'utiliser. Il servira de base pour discuter de votre projet avec votre tuteur, et élaborer le workflow qui mettra ces analyses en oeuvre.  

## Plan de gestion des données

Au fil des semaines de formation, chaque apprenant sera amené à définir un plan de gestion des données (PGD, ou DMP pour Data Management Plan) pour son projet tutoré. 

### Vidéoconférence pour le démarrage de votre PGD

Nous organiserons le 13 mars de 10h à 12h une vidéoconférence pour vous aider à démarrer votre PGD.

Instructions de connexion: **<https://tinyurl.com/dubii-visio>**

Deux heures ne suffiront pas, loin s'en fait, pour disposer d'un PGD complet, mais les animateurs pourront 

- vous expliquer les principes généraux
- vous indiquer comment créer un premier jet de PGD sur OPIDoR
- répondre à vos questions sur la façon d'organiser votre PGD.

Vous pourrez ensuite poursuivre la description du PGD, qui vous demandera sans doute de discuter avec les différents acteurs ilmpliqués dans votre projet (plateformes de production des données, bioinformaticiens de vos labos, biologistes qui participent aux expériences, ...). 

Informations concernant les projets tutorés du Diplôme Universitaire en Bioinformatique Intégrative

### Intervenants

1. Paulette Lieby, IFB-core
2. Jean-François DUfayard, IFB
3. Frédéric de Lamotte, INRAe ([0000-0003-4234-1172](https://orcid.org/0000-0003-4234-1172))
4. Jacques van Helden, IFB-core ([0000-0002-8799-8584](https://orcid.org/0000-0002-8799-8584))
5. Hélène Chiapello, IFB
6. Bertrand Cosson, Université de Paris
7. Pierre Poulain, Université de Paris

### Ressources

| Nom | Description | URL |
|------------|----------------------------|--------------------|
| OPIDoR DMP | Outil de création de PGD, dépôt ***temporaire*** | <https://dmp.opidor.fr/plans> |
| OPIDoR DMP | Une sélection de modèles de PGD | <https://dmp.opidor.fr/public_templates> | 
| OPIDoR DMP | Quelques PGDs rédigés et publics | <https://dmp.opidor.fr/public_plans> | 
|            | Quelques slides PGD | <https://github.com/DU-Bii/projets-tutores-DUBii/blob/master/12_gestion-des-donnees_pl.pdf> |

### Guide PGD : commencer à rédiger un Plan de Gestion de Données

* s'assurer que l'on ait un compte pour accéder à DMP Opidor à <https://dmp.opidor.fr/> 
* une fois connecté, aller sur l'onglet "Modèles de DMP" (cliquer) : s'affichera une liste de modèles PGD. Il s'agit de choisir un de ces modèles comme base du PGD à créer et rédiger
* chercher le modèle "INRAE - Trame générique projet" (note : ceci n'est pas une obligation, on peut choisir un modèle alternatif ; tous les modèles permettent de renseigner les éléments soulignés ci-dessous, de manière plus ou moins explicite) ; cliquer sur l'icon "+" : ceci va créer un nouveau PGD dans votre compte avec comme base le modèle choisi.
* la rédaction du PGD peut démarrer

### Éléments qui doivent figurer à minima dans le plan

1. **Description des données**
	- types de données (généralement 2 ou 3 omiques différentes)
	- nombre d'échantillons, conditions, ...
	- origine des données (quelles plateformes produisent chaque type de données)

2. Estimation du **volume des données à téléverser** dans l'espace-projet
	- données propres
	- données importées (par exemples d'autres publications)

3. Estimation du **volume des données générées** par les workflows pendant la phase d'analyse.

4. Que deviendront les données à l'issue du projet tutoré (fin juin) ?
	- Poursuite des analyses sur le cluster IFB-core (ou autre serveur utilisé pendant le tutorat) ?
	- Rapatriement vers les ordinateurs de votre institut ?
	- Transfert vers d'autres serveurs ?

5. Y a-t-il une solution pour assurer la **conservation sécurisée** de ces données ?
	- pendant la durée du projet
	- à l'issue du projet (éventuellement via les dépôts internationaux)
	
	**Avertissement / rappel** : les serveurs de calcul de l'IFB offrent un service de *stockage à chaud*, sans garantie de pouvoir les retrouver en cas de pépin (effacement accidentel, panne de nos machines...)

6. **Préservation à long terme**. 
	- A l'issue du projet, quelle partie des données devra être préservée, et quelle partie pourra être effacée ?
	- Avez-vous identifié des centres de stockage qui assureront la préservation à long terme (indépendamment des dépôts) ?

7. **Accessibilité**
	- dans quels dépôts ces données seront-elles entreposées ?
	- quel sera leur statut d'accessibilité ?
	- à quel moment seront-elles transférées dans les dépôts ?
		- pendant le projet, avec un éventuel embargo ?
		- à l'issue du projet ,

# Description de vos métadonnées


