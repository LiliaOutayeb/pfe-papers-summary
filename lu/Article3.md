## Article (3) : Uncertainty Estimation and Quantification for LLMs: A Simple Supervised Approach (2024)
### Auteurs
Liu, et al.

### Lien
[Lire l’article](https://drive.google.com/file/d/1Od7v0-o7HfgTPBnsBJgm7-nsrUDRp4jb/view?usp=sharing)

### Résumé
L’article propose une estimation supervisée de l’incertitude des LLM : on crée un jeu d’entraînement où chaque réponse est accompagnée d'une une mesure de qualité puis on apprend une régression qui prédit un score de confiance. Trois régimes sont étudiés : Wb‑S ( **white-box** accès aux activations internes ), Gb‑S (**Grey-box** features probabilistes/entropie) et Bb‑S (**black box**)

**Approche supervisée** : première formalisation du problème d’incertitude comme régression à partir de réponses labellisées, alors que les enquêtes se concentrent sur des métriques non‑supervisées ou des détecteurs heuristiques


 <h3>Points clés</h3>

 - Les expériences montrent que les modèles supervisés surpassent les baselines non‑supervisées et améliorent la calibration, même en out‑of‑distribution QA
 - **Utilisation des activations cachées** : démonstration que les neurones internes contiennent de l’information d’incertitude, exploitée uniquement dans le mode white‑box
 - Applicabilité aux modèles fermés : le régime black‑box (Bb‑S) permet d’estimer l’incertitude d’un LLM propriétaire en utilisant un "LLM tool" ouvert
 - les activations internes du modèle (états cachés) contiennent un signal d’incertitude suffisamment puissant pour être appris par une régression supervisée, ce qui permet de prédire un score de confiance directement corrélé aux hallucinations. Cette approche « white‑box » montre que, contrairement aux travaux antérieurs qui se limitaient à des métriques de sortie (logits, entropie) ou à des méthodes non‑supervisées, on peut exploiter les représentations internes du LLM pour détecter et quantifier les hallucinations de façon plus précise et calibrée

---
## To be continued


---



