# Elyne Lab Director (ELD)

**Français · [English](README.en.md)**

ELD organise les campagnes de qualification en laboratoire. Il vérifie le périmètre, l'état préalable, les preuves et les portes de reprise ; il déclenche les étapes approuvées, consolide les résultats et produit un rapport traçable. Elyne Red choisit et exécute ses actions offensives dans le scénario autorisé ; ELD garde la conduite du laboratoire. Le catalogue présente ELD au statut **Laboratoire**.

Le moteur peut suivre un parcours **déterministe**. Un modèle local, tel que Bonsaï, peut aider à analyser ou proposer des étapes, sans remplacer les contrôles de périmètre ni l'attestation de l'opérateur.

| Point clé | État démontré |
| --- | --- |
| Prévol, journal et rapport | Fonctionnels dans le kit de laboratoire. |
| Snapshot VMware chiffré | Création et restauration réalisées par l'opérateur, puis attestées et revérifiées. |
| Reprise automatique après restauration | Non établie pour l'essai H ; l'état ELD est resté `RESTORING`. |

## À consulter

- [Architecture et portes de contrôle](docs/architecture.md)
- [Kits de démonstration G/H et limites](docs/evidence.md)
- [Droits et conditions de consultation](NOTICE.md)

ELD est un produit distinct d'EAS Défense et d'Elyne Red Unifiée. Un code retour 0 du lanceur ou une attestation humaine ne constituent pas, seuls, un verdict PASS de la défense. Ce dépôt est documentaire ; il ne contient ni état de campagne, ni configurations de VM, ni reçus bruts. [Contacter Elyne Corp](mailto:admin@elynecorp.fr) · [Catalogue](https://elynecorp.fr/).
