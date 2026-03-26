## Article (3) : Uncertainty Estimation and Quantification for LLMs: A Simple Supervised Approach (2024)
### Auteurs
Liu, et al.

### Lien
[Lire l’article]([https://drive.google.com/file/d/1DJmuUvLvFG8_ge9-4-gFXEZM51Rdgwg-/view?usp=drive_link](https://drive.google.com/file/d/1Od7v0-o7HfgTPBnsBJgm7-nsrUDRp4jb/view?usp=drive_link))

### Résumé
L’article propose une estimation supervisée de l’incertitude des LLM : on crée un jeu d’entraînement où chaque réponse est accompagnée d'une une mesure de qualité puis on apprend une régression qui prédit un score de confiance. Trois régimes sont étudiés : Wb‑S ( **white-box** accès aux activations internes ), Gb‑S (**Grey-box** features probabilistes/entropie) et Bb‑S (**black box**)

**Approche supervisée** : première formalisation du problème d’incertitude comme régression à partir de réponses labellisées, alors que les enquêtes se concentrent sur des métriques non‑supervisées ou des détecteurs heuristiques


 <h3>Points clés</h3>

 - Les expériences montrent que les modèles supervisés surpassent les baselines non‑supervisées et améliorent la calibration, même en out‑of‑distribution QA
 - **Utilisation des activations cachées** : démonstration que les neurones internes contiennent de l’information d’incertitude, exploitée uniquement dans le mode white‑box
 - Applicabilité aux modèles fermés : le régime black‑box (Bb‑S) permet d’estimer l’incertitude d’un LLM propriétaire en utilisant un "LLM tool" ouvert
---
##To be continued


---



