# familywatch-lists

Listes de domaines utilisées par l'extension FamilyWatch (contrôle parental).

- `blacklist.json` : domaines bloqués (environ 9 000). Les sous-domaines sont bloqués automatiquement.
- Pour forcer la mise à jour chez les utilisateurs, modifier le champ `version`.

## Sources

- Liste curée par FamilyWatch (sites pour adultes, webcams, rencontres pour adultes, jeux d'argent).
- `pi_blocklist_porn_top1m.list` de [chadmayfield/my-pihole-blocklists](https://github.com/chadmayfield/my-pihole-blocklists), sous licence GPL-3.0 (dernière mise à jour de la source : 2020).
- `pornsite-list.txt` de [sibaram-sahu](https://gist.github.com/sibaram-sahu/5248d7600a24284f580219b29d178c49) (gist, sans licence indiquée, mis à jour en octobre 2026).

Cette liste peut contenir des faux positifs (par exemple `4chan.org`, `dmm.com`) : un parent peut les autoriser via la liste blanche de l'extension.

