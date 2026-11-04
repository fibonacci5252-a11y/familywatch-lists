# familywatch-lists

Listes de domaines utilisées par l'extension FamilyWatch (contrôle parental).

- `blacklist.json` : domaines bloqués (environ 9 000). Les sous-domaines sont bloqués automatiquement.
- Pour forcer la mise à jour chez les utilisateurs, modifier le champ `version`.

## Sources

- Liste curée par FamilyWatch (sites pour adultes, webcams, rencontres pour adultes, jeux d'argent).
- `pi_blocklist_porn_top1m.list` de [chadmayfield/my-pihole-blocklists](https://github.com/chadmayfield/my-pihole-blocklists), sous licence GPL-3.0 (dernière mise à jour de la source : 2020).

Cette liste peut contenir des faux positifs (par exemple `4chan.org`, `dmm.com`) : un parent peut les autoriser via la liste blanche de l'extension.

