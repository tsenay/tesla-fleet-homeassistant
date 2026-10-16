# Model Y Juniper — Solid Black (`black`)

Squelette de pack d'images. Déposez ici les 7 photos JPEG, puis supprimez ce
fichier. Voir `docs/pack-images.md` pour les règles de cadrage et de mesure.

Fichiers attendus (fond `#141414`) :

| Fichier | Taille (px) | Contenu |
| --- | --- | --- |
| `topdown.jpg` | 720 × 1284 | Vue de dessus, nez en haut, ~2 % de marge. |
| `topdown-plugged.jpg` | 720 × 1284 | Idem, câble branché. |
| `topdown-charging.jpg` | 720 × 1284 | Idem, en charge. |
| `side.jpg` | 660 × 400 | Vue ¾ au repos, centrée. |
| `side-plugged.jpg` | 660 × 400 | Même cadrage, câble branché. |
| `side-charging.jpg` | 660 × 400 | Même cadrage, en charge, câble visible. |
| `climate.jpg` | 720 × 1200 | Intérieur vu de dessus. |

Règle clé : les trois photos `side*` doivent montrer la voiture à la même
taille, au même endroit, sur le même canvas. Vérifier par la mesure, pas à
l'œil (voir `docs/pack-images.md`).

Après avoir ajouté les photos, pensez à déclarer le pack dans `PACKS_SHIPPED`
(`tesla-fleet-card.js`) avec `gen: "juniper"`.
