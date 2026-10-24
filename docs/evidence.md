# Elyne Lab Director — preuves et limites

**Français · [English](evidence.en.md)**

| Source datée | Observation | Limite |
| --- | --- | --- |
| Kit de démonstration G, octobre 2026 | Les traces internes du kit décrivent une séquence chronométrée et des classements par l'oracle Red. | Le porteur a précisé qu'aucune nouvelle campagne Red Team qualifiante n'a été menée le 19 octobre. Ces comptes ne sont pas publiés comme résultats de défense. |
| Kit de démonstration G, restauration | L'opérateur a restauré le snapshot dans VMware ; des contrôles hôte/invité ont ensuite été observés. | Le processus ELD est resté à l'étape de restauration/vérification : clôture automatique non démontrée. |
| Kit de démonstration H, 19 octobre 2026 | Restauration du snapshot attestée par l'opérateur. | ELD est resté `RESTORING`, avec `SAFE_TO_CONTINUE=false` ; aucun PASS final. |
| Catalogue public, consulté le 24 octobre 2026 | ELD est indiqué « Laboratoire ». | Statut commercial déclaré. |

Le kit documente une orchestration courte de démonstration ; il ne démontre ni une démo entièrement automatique en un clic ni un nouveau verdict de campagne Red Team. Un code retour `0` du lanceur indique seulement que ce processus s'est terminé : il ne change ni un état `RESTORING`, ni un verdict **INCONCLUSIVE** en PASS.
