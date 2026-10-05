<!-- ELUCENIA technical documentation · escala-de-resultados-de-glasgow · fr · no clinical/professional/rights approval -->

# Échelle de devenir de Glasgow (GOS)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-de-resultados-de-glasgow)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Situation du patient

`gos`

- `1` — 1 – Décès
- `2` — 2 – État végétatif persistant : aucune réponse significative, cycles veille-sommeil
- `3` — 3 – Handicap sévère : conscient, mais dépendant d’une autre personne au quotidien
- `4` — 4 – Handicap modéré : autonome, mais avec des séquelles (peut utiliser les transports et travailler en milieu protégé)
- `5` — 5 – Bonne récupération : reprend une vie normale malgré des déficits mineurs

## Édition de la méthode

GOS/Jennett–Bond 1975 : 5 catégories ; favorable 4–5 ; pas la GOSE à 8 catégories

## Formule documentée

Choisissez la catégorie la plus adaptée. Les études dichotomisent généralement en favorable (4 et 5) et défavorable (1 à 3).

## Limites et population

Évalue le résultat fonctionnel après une lésion cérébrale en tenant compte du handicap physique et mental. Enregistrez le temps de suivi et l’édition à cinq catégories. La GOS ne doit pas être considérée comme équivalente à la GOSE à huit catégories ni comme une prédiction à partir des données d’admission.

## Références

- [Jennett B, Bond M. Assessment of outcome after severe brain damage: a practical scale. Lancet, 1975.](https://doi.org/10.1016/S0140-6736(75)92830-5)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
