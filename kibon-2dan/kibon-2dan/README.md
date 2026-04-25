# Kibon 2è Dan – Cartes individuelles

Cartes techniques du Module A – Kibon 2è Dan (FFTDA / CSDGE).

## Structure

```
cards/
  membres-superieurs-positions/               # 8 cartes – bleu
  membres-inferieurs/                         # 8 cartes – vert
  membres-superieurs-inferieurs-positions/    # 8 cartes – jaune
data/
  cards.json    # Métadonnées complètes
```

## Catégories

| Couleur | Slug | Contenu |
|---------|------|---------|
| 🔵 Bleu  | `membres-superieurs-positions` | Enchaînement membres supérieurs + positions |
| 🟢 Vert  | `membres-inferieurs` | Enchaînement membres inférieurs |
| 🟡 Jaune | `membres-superieurs-inferieurs-positions` | Enchaînement membres supérieurs + inférieurs + positions |

## data/cards.json

Chaque carte contient : `id`, `category`, `number`, `title`, `techniques[]`, `image`.
