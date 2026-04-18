# Geng et al. (Mai 2024)
## "A Survey of Confidence Estimation and Calibration in Large Language Models"
### Référence complète : 
Geng, J., et al. (2024). A Survey of Confidence Estimation and Calibration in Large Language Models.
### Type : Thématique technique.
### Scope : Estimation de confiance et Calibration (fondations de la détection d'hallucinations).
## Lien avec l'hallucination : L'incertitude est utilisée comme signal de détection.
### Taxonomie :
- Estimation en Boîte blanche : Basée sur les logits et les états internes.
- Estimation en Boîte noire : Confiance linguistique (verbalisation) et auto-cohérence.
### Détection : 
Utilisation de modèles "surrogates" pour estimer la confiance.
### Mitigation : 
Calibration post-hoc (Platt scaling, Isotonic regression) et durant l'ICL (calibration de batch).
