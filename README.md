# HIKARI Design System

<p align="center">
  <strong>Système de design React + Tailwind CSS pour PropTech</strong>
</p>

## Installation

```bash
npm install @hikari/design-system
```

## Utilisation

```jsx
import { StatCard, Badge, Button } from "@hikari/design-system";

<StatCard label="Rentabilité" value="7.2%" color="#34d399" />
```

## Composants

| Composant | Description |
|---|---|
| `StatCard` | Carte de statistique avec label, valeur, couleur |
| `Badge` | Badge avec variantes de couleur |
| `Button` | Bouton avec variantes (primary, ghost, outline) |
| `DataTable` | Tableau de données paginé |
| `ScoreGauge` | Jauge circulaire de score /100 |

## Design tokens

| Token | Valeur |
|---|---|
| `--background` | Dark navy (#0a0f1e) |
| `--primary` | Gold (#f59e0b) |
| `--card` | Dark slate (#121826) |
| `--border` | Subtle (#1e2a3a) |

## Thème

Le système supporte le mode sombre par défaut, avec un mode clair optionnel.

## Licence

MIT © HIKARI GROUP