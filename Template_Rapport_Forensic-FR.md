# 🧾 Rapport d’Analyse Forensic

## 1. Synthèse (Executive Summary)

Présentation concise de l’analyse, des objectifs et des résultats principaux.

Exemple :  
Ce rapport présente l’analyse forensic d’une image disque visant à identifier des activités suspectes.  
Les résultats mettent en évidence des actions utilisateur incluant la suppression de fichiers et l’exécution de programmes externes.  
Aucune preuve d’exfiltration de données n’a été identifiée.

---

## 2. Périmètre & Objectifs

**Périmètre :**
- Type de données : (image disque, clé USB, logs…)  
- Système : (Windows / Linux…)  
- Origine des données : (environnement simulé / test)  

**Objectifs :**
- Identifier des activités suspectes  
- Reconstituer les actions utilisateur  
- Extraire les artefacts pertinents  

---

## 3. Méthodologie

**Outils utilisés :**
- Autopsy  
- Sleuth Kit  
- (autres si besoin)

**Approche :**
- Analyse de timeline  
- Extraction d’artefacts  
- Analyse du système de fichiers  

**Intégrité des données :**
- Vérification des hash (si applicable)

---

## 4. Environnement technique

- Système analysé :  
- Système de fichiers :  
- Format de l’image :  
- Environnement des outils :  

---

## 5. Analyse & Résultats

### 5.1 Activité utilisateur

**Observation :**  
Décrire ce qui a été identifié  

**Artefact :**  
Source (logs, MFT, registre…)  

**Interprétation :**  
Analyse et signification  

---

### 5.2 Fichiers supprimés

**Observation :**  
...  

**Artefact :**  
...  

**Interprétation :**  
...  

---

### 5.3 Exécution de programmes

**Observation :**  
...  

**Artefact :**  
...  

**Interprétation :**  
...  

---

### 5.X Autres éléments

(Ajouter des sections selon les résultats)

---

## 6. Chronologie des événements

| Date | Événement | Source |
|------|----------|--------|
|      |          |        |

---

## 7. Conclusion

Synthèse claire des résultats.

Exemple :  
L’analyse met en évidence une activité utilisateur inhabituelle incluant la suppression de fichiers et l’exécution de programmes.  
Toutefois, aucun élément ne permet de confirmer une exfiltration de données.

---

## 8. Limites de l’analyse

- Jeu de données limité  
- Absence d’analyse mémoire  
- Logs partiels  

---

## 9. Annexes

- Captures d’écran (Autopsy, logs…)  
- Extraits de données  
- Valeurs de hash  

---

## ⚖️ Avertissement

Ce rapport est basé sur un jeu de données simulé à des fins pédagogiques.


<!---
🔥 Comment l’utiliser intelligemment

👉 Dans ton repo :

/report.md → ce template rempli
/data/ → petits extraits (si possible)
/screenshots/ → captures Autopsy

💡Ajoute en haut du repo :
## 📌 Project Description
This project demonstrates a forensic analysis workflow on a simulated dataset, including artefact extraction, timeline reconstruction, and technical reporting.

Tu peux renommer le titre :

👉 Rapport d’analyse numérique (forensic)

➡️ encore plus compréhensible côté non-tech (assurance / client)
--->
