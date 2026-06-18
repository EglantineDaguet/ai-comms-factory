Dernière mise à jour : 18 juin 2026

# Carte de navigation du système AI Comms Factory

Ce fichier explique comment ce coffre est organisé et où trouver chaque type d'information. Il ne contient pas l'information elle-même : il dit où elle se trouve. Quand tu travailles dans ce coffre, lis ce fichier en premier pour savoir où chercher.

---

## Qui je suis

AI Comms Factory, entreprise individuelle créée en septembre 2025 par Eglantine Daguet, basée à Genève. Conseil en IA appliquée aux fonctions communication et marketing. Le détail est dans `00_Contexte/entreprise`.

---

## Principe de fonctionnement

- **Source unique de vérité** : chaque information n'existe qu'à un seul endroit. Si tu as besoin du positionnement, va le chercher dans son fichier d'origine, ne le recopie pas.
- Les fichiers de `00_Contexte` sont l'ADN permanent. Ils changent rarement et font foi.
- Les fichiers de `01_Content` sont le territoire de communication. Ils guident la production éditoriale.
- Les fichiers de `02_Skills` sont les formats exécutables. Charge le Skill correspondant au type de contenu demandé.
- Le travail courant (clients, contenus, projets) s'appuie sur ce socle sans le dupliquer.

---

## Où trouver quoi

### 00_Contexte — l'ADN permanent de l'entreprise

- `00_Contexte/entreprise` : identité, légitimité de la fondatrice, ancrage suisse, raison d'être, vocabulaire propriétaire (Factory Shift, Factory, Reveal / Rethink / Build / Elevate).
- `00_Contexte/vision-mission` : la conviction fondatrice, le Factory Shift, "amplifier sans renoncer", la vision long terme.
- `00_Contexte/offre` : les quatre offres, ce que chacune produit, les prix.
- `00_Contexte/strategie` : cibles (prioritaire et secondaire), positionnement face au marché, canaux d'acquisition, indicateurs de pilotage.

### 01_Content — le territoire de communication

- `01_Content/tone-of-voice` : la voix de la marque. Cinq traits définissants, ce qu'on dit et comment, ce qu'on n'écrit jamais. À charger pour tout contenu produit.
- `01_Content/brand-system` : identité visuelle, palette (`#3A0088` violet signature, `#0FEBE0` cyan, `#F5F1EA` ivoire, et les autres), typographie (Playfair Display / Neue Einstellung), principes de mise en page, iconographie narrative. À charger pour tout brief visuel.
- `01_Content/content-pillars` : les quatre piliers éditoriaux (Cas d'usage et Méthode / Gouvernance et Risque / Regard extérieur / Terrain), avec leurs angles, exemples de sujets et formats recommandés.
- `01_Content/objectifs-de-communication` : objectifs 2026 (RDV commerciaux en priorité, autorité en levier), canaux actifs (LinkedIn en priorité, blog en développement), cadence, KPIs.

### 02_Skills — les formats de production de contenu

Un fichier par type de contenu. Charger le Skill correspondant avant de produire.

- `02_Skills/copywriter-linkedin` : produire des posts LinkedIn dans la voix d'Eglantine. Quatre modes (scan actu / planification / développement de post / brief visuel), piliers éditoriaux, règles de voix, vocabulaire interdit, checklist avant livraison.
- `02_Skills/veille-ia` : produire la veille IA + communication. Scan en profondeur des newsletters généralistes en priorité, puis toutes les autres sources de `03_Veille/sources_veille.md`, signaux rattachés aux piliers, rubrique outils et démos pour les équipes com, analyse de fond. À charger pour tout scan de veille.

**Skills techniques dans Cowork** (ne pas dupliquer dans Obsidian) :

- `DOCX brandé` : créer des documents Word aux couleurs AI Comms Factory. Skill disponible dans Cowork à `/mnt/skills/user/ai-comms-factory-docx/SKILL.md`. Utilise le template `.docx` et les scripts XML du serveur.
- `PPTX brandé` : créer des présentations aux couleurs AI Comms Factory. Skill disponible dans Cowork à `/mnt/skills/user/ai-comms-factory-pptx/SKILL.md`. Utilise le template `.pptx` en format ultra-wide 20" × 11.25" et un catalogue de 18 slides.

### 03_Veille — ce que je capture pour rester à jour

- `03_Veille/sources_veille` : la liste des sources de référence pour la veille IA + communication. Newsletters, auteurs LinkedIn, blogs officiels des éditeurs (Anthropic, OpenAI, Google, Microsoft), outils image et vidéo, médias spécialisés communication (La Réclame, Blog du Modérateur, Stratégies), médias internationaux, études et rapports annuels. À consulter en priorité pour tout scan d'actualité.

Les notes de veille capturées au fil de l'eau (articles intéressants, études, citations) vivent dans ce même dossier, en fichiers datés.

### 04_Clients — une Factory par client

Chaque client a son propre dossier avec son propre `claude.md`, son contexte, ses décisions, ses sessions et ses livrables. Ne jamais mélanger le contexte d'un client avec celui d'un autre.

### 05_Projets — initiatives ponctuelles mais longues

À créer si besoin.

---

## Comment utiliser les Skills

Quand une tâche de production de contenu est demandée :

1. Charger `01_Content/tone-of-voice` (toujours).
2. Charger le Skill correspondant dans `02_Skills/`.
3. Si un visuel est impliqué, charger aussi `01_Content/brand-system`.
4. Produire en appliquant les règles du Skill, pas en improvisant.

---

## Règles générales de travail

- Respecter toujours la voix définie dans `01_Content/tone-of-voice`.
- Ne jamais inventer un chiffre ou une référence : si une donnée n'est pas dans les fichiers, le dire.
- Ne jamais utiliser le tiret cadratin en milieu de phrase.
- Quand une information manque, proposer de créer le fichier qui devrait la contenir, à l'endroit logique de cette carte.
- Ne jamais mélanger le contexte d'un client avec celui d'un autre ou avec le contexte général d'AI Comms Factory.