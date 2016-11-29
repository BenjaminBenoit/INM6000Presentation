class: center, middle

# La Neutralité du Net : un combat continu sur plusieurs fronts

##### Frédéric Vachon, Karl St-Cyr et Benjamin Rosa

---

# La Neutralité du Net défend 4 principes

* La transmission des données par les opérateurs sans en examiner le contenu.

* La transmission des données sans prise en compte de la source ou de la destination des données.

* La transmission des données sans privilégier un protocole de communication.

* La transmission des données sans en altérer le contenu.


---

# Principales fonctionnalités

* Lancer des tâches de Fuzzing

* Consulter les tâches en cours

* Consulter les rapports de crash

* Définir une grammaire balisant les données à générer


---

## Contenu des sprints


* Sprint 1
	* Préparer l’environnement de développement
	* Le visiteur peut se créer un compte utilisateur 
	* L’utilisateur peut se connecter et se déconnecter de l’application
	* L’utilisateur peut créer une tâche de fuzzing simplifiée ne contenant que le programme à tester

* Sprint 2
	* Démarrer une tâche de fuzzing en définissant une grammaire de base pour injecter des données dans un programme.
	* Fuzzer un programme via l’entrée standard.
	* Consulter la liste des rapports de crash.
	* Consulter la liste des tâches de fuzzing.

* Sprint 3
	* Consulter les détails d’un crash
	* Consulter les détails d’une tâche de fuzzing
	* Forcer l’arrêt d’une tâche de fuzzing

---

# Contenu du sprint actuel

* Démarrer une tâche de fuzzing en définissant une grammaire de base pour injecter des données dans un programme.


* Fuzzer un programme via l’entrée standard.


* Consulter la liste des rapports de crash.


* Consulter la liste des tâches de fuzzing.

---
class: center, middle

# Démo
---

# Diagramme de classe

```











```
![](./img/diag_classe_2.png)


---
class: center, middle

# Le code
---

### Revue de sprint

#### Revue technique

\+ Tâches accomplies dans les temps prévus

\- Framework peu documenté rend la tâche plus difficile

\- Contrainte temporelle fait qu'on a dû utiliser un design architectural moins robuste


#### Revue gestion

\+ Bon transfert de connaissance entre les membres de l'équipe

\- Commencement tardif du travail

#### Améliorations prévues

* Commencer le travail dès le jour 1 du sprint

---

### Plan du prochain sprint


1. En tant qu’utilisateur je peux consulter les détails d’un crash afin de connaître les causes exactes qui ont conduits le programme à être interrompu.
	- 16 heures

2. En tant qu’utilisateur je peux consulter les détails d’une tâche de fuzzing afin de connaître le statut de chacune d’entre elles.
	- 16 heures

3. En tant qu’utilisateur je peux forcer l’arrêt d’une tâche de fuzzing afin de libérer des ressources pour d’autres tâches de fuzzing.
	- 9 heures
