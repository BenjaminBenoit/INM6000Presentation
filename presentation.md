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

## Les parties prenantes au débat de la Neutralité du Net


* La société civile
	* Organisations fondées de façon autonome.
	* Défendent l’intérêt des citoyens indépendamment de l’influence des entreprises et des États.
	* Electronic Fountier Foundation : défend les libertés civiles dans le domaine du numérique.
	* D'autres acteurs plus surprenant : Christian coalition of America.

* Les Fournisseurs de Contenu Internet
	* Google, Amazon, Ebay, Netflix, Facebook etc..
	* Militent activement pour la protection de la Neutralité du Net.
	* Ne veulent pas payer les FAI pour pouvoir mettre leur contenu sur Internet.
	* La réglementation permet de ne pas créer de barrière à l'entrée empêchant ainsi de nouveaux joueurs d'arriver sur le marché.
	* La Neutralité du Net permet aux FCI de grande envergure d'éviter de grosses dépenses.

* Les Fournisseurs d'Accès Internet
	* Largement en défaveur de la Neutralité du Net.
	* Considèrent que la réglementation nuit à l'investissement dans de nouvelles infrastructures réseaux.
	* Ne souhaitent pas payer pour les FCI.
	* Veulent plus de contrôle sur les utilisateurs, afin d'éviter des congestions du réseaux.

---
* Les Gouvernements



---

# État de la Neutralité du Net dans une partie du monde :

* Canada
	* Depuis 2009, les FAI doivent fournir leur politiques de management de leur réseau et du trafic au CRTC.
	* En revanche le CRTC n'a aucun pouvoir contraignant sur les FAI.
	* Le Canada reconnait le principe de Neutralité du Net mais ne le défend pas.

* États-Unis
	* Après plusieurs revirements, en 2015 la FCC interdit finalement les 'Fast-lane'.
	* La FCC impose la transparence dans l’opération des réseaux.
	* Le principe de Neutralité du Net est reconnu et soutenu par les lobby puissant des FCI de la Silicon Valley.
	* La Neutralité du Net pourrait être en danger si on se fie aux dernières déclarations du futur président Américain.

* Europe
	* 2016 : l'Union Européenne consacre la défense de la Neutralité du Net dans sa forme la plus stricte
	* En France, l'ARCEP a le pouvoir de contrôler et de sanctionner les FAI qui enfreigne la Neutralité du Net.
	* Seul exception : le Zero-Rating reste autorisé


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
