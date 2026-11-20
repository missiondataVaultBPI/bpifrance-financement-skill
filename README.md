# Aides publiques et financement : un skill Claude

Un skill pour **se renseigner sur les aides publiques françaises** (Bpifrance, Régions, formation, crédits d'impôt) et **préparer un dossier ou un devis finançable**, avec **l'URL officielle et un extrait pour chaque affirmation**.

> **Version bêta : testez le skill et signalez les erreurs (onglet *Issues*).** Il n'a pas encore été évalué à grande échelle.
>
> **Ce projet n'est affilié ni à Bpifrance, ni aux Régions, ni à l'État.** Il synthétise des pages publiques lues les 19 et 20 novembre 2026 (version **2026-11-20**). Ce n'est **ni un avis juridique, ni un avis fiscal, ni un conseil financier**. Une aide n'est jamais garantie : elle est demandée par le bénéficiaire et décidée par l'organisme qui la gère. Vérifiez toujours auprès de l'organisme avant de signer ou de payer quoi que ce soit.

## Contenu
- `aides-publiques-financement/SKILL.md` : les règles de réponse et les deux modes (se renseigner, préparer un dossier).
- `aides-publiques-financement/references/fiches/` : 12 fiches par dispositif ou famille de dispositifs.
- `references/guide-devis-partie-*.md` : guide pour structurer un devis finançable.
- `references/matrice-profils-dispositifs.md`, `checklist-client.md`, `sources.md`.

## Comment les sources sont vérifiées
Chaque fiche se termine par une table « Affirmations et sources » : affirmation, étiquette de fiabilité, extrait mot pour mot (25 mots maximum), URL, note d'origine. Avant chaque publication, un script vérifie que chaque URL provient bien de la note source citée et que chaque extrait y figure à l'identique (les notes sources ne sont pas dans ce dépôt). Il ne vérifie pas que l'extrait justifie la phrase : relisez la source avant de vous en servir. Les extraits marqués « lecture reformulée » ont été lus par un outil qui reformule le texte : ils ne sont pas citables tels quels.

Étiquettes : `[ÉCRIT]` page officielle lue · `[DÉDUIT]` non écrit tel quel · `[NON PUBLIÉ]` aucune source · `[NON VÉRIFIÉ]` · `[RECOMMANDATION]` conseil de méthode.

## Installer
Copiez le dossier `aides-publiques-financement/` dans `~/.claude/skills/` (Claude Code), ou importez-le comme skill dans votre client Claude.

## Limites connues
Bretagne partielle ; certains règlements en PDF illisibles par les outils (Normandie, Nouvelle-Aquitaine) ; règlement Innov'up (2021) à vérifier ; règles de sous-traitance, de « dépense engagée » et de « sous condition » non publiées ; subrogation TVA chez Atlas non confirmée.

## Corrections
Une erreur, une règle périmée, une source meilleure ? Ouvrez une *issue* avec l'URL de la page officielle. La base est régénérée à partir de ses sources, avec une date de version.

## Licence et droits
Les textes cités restent la propriété de leurs auteurs (Bpifrance, Régions, administrations). Seuls de courts extraits, avec leur URL, sont reproduits. Aucune licence n'est définie pour ce dépôt : vous pouvez le consulter et le tester ; pour toute réutilisation, contactez l'auteur via une issue.
