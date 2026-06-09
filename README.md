# Claude Skill — Trouver son Ikigaï

Ce dépôt contient un skill Claude destiné à accompagner une personne dans la recherche de son Ikigaï, à partir des principes pratiques de l'ouvrage de Christie Vanbremeersch, *Trouver son Ikigaï*.

Le skill ne sert pas à résumer l'ouvrage. Il sert à guider une personne dans une démarche d'orientation : clarification, recentrage, exploration, expérimentation, viabilisation et ajustement.

## Structure du dépôt

```text
claude-skill-trouver-son-ikigai/
├── SKILL.md
├── README.md
└── references/
    ├── 01_cadre_ikigai.md
    ├── 02_parcours_guidage.md
    ├── 03_exercices.md
    ├── 04_questions_puissantes.md
    ├── 05_modeles_sortie.md
    ├── 06_garde_fous.md
    └── 07_signaux_et_diagnostics.md
```

## Fichier central

Le fichier `SKILL.md` est le pilier du skill. Il définit :

- le rôle de Claude ;
- les déclencheurs d'utilisation ;
- la posture ;
- la méthode générale ;
- les règles de réponse ;
- les références à consulter dans le dossier `references/`.

## Références internes

Les fichiers du dossier `references/` apportent les détails nécessaires :

- `01_cadre_ikigai.md` : définition de l'Ikigaï, quatre pôles, profils d'utilisateurs.
- `02_parcours_guidage.md` : parcours d'accompagnement progressif.
- `03_exercices.md` : exercices pratiques inspirés de la démarche du livre.
- `04_questions_puissantes.md` : banque de questions pour guider l'introspection.
- `05_modeles_sortie.md` : modèles de réponses et d'ateliers.
- `06_garde_fous.md` : limites, précautions et posture éthique.
- `07_signaux_et_diagnostics.md` : repérage des blocages et choix des interventions.

## Usage prévu

Ce skill est conçu pour aider Claude à répondre à des demandes comme :

- "Aide-moi à trouver mon Ikigaï."
- "Je veux me reconvertir mais je ne sais pas vers quoi."
- "Je sais ce que j'aime, mais je ne sais pas comment en vivre."
- "Je suis dispersé, aide-moi à me recentrer."
- "Je veux transformer une passion en projet viable."
- "Je veux un atelier d'introspection sur mon orientation."

## Philosophie du skill

La recherche d'Ikigaï est traitée comme un chemin vivant, non comme une révélation magique.

Le skill privilégie :

- le carnet ;
- les questions récurrentes ;
- la curiosité ;
- les petits pas ;
- les tests ;
- les retours d'expérience ;
- la clarté sur l'argent ;
- la célébration des progrès ;
- l'équilibre entre vocation, contribution et réalité matérielle.

## Installation

Place le dossier complet dans l'environnement de skills de Claude. Le fichier `SKILL.md` doit rester à la racine du dossier, et les fichiers de référence doivent rester dans `references/`.
