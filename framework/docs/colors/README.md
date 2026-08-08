# Documentation — Couleurs (`colors`)

Système de couleurs utilitaires basé sur **20 familles de couleurs réelles**.

## 1. 20 Familles de Couleurs

`red`, `orange`, `amber`, `yellow`, `lime`, `green`, `emerald`, `teal`, `cyan`, `sky`, `blue`, `indigo`, `violet`, `purple`, `fuchsia`, `pink`, `rose`, `slate`, `gray`, `zinc`

## 2. Nuances Disponibles

`50`, `100`, `200`, `300`, `400`, `500`, `600`, `700`, `800`, `900`, `950`

## 3. Utilitaires Fond, Texte & Bordure

| Mot-clé | Exemple de classe | Résultat |
|---|---|---|
| Raccourci fond (500 par défaut) | `bg-blue` | `background-color: var(--cc-blue-500);` |
| Fond avec nuance | `bg-blue-600` | `background-color: var(--cc-blue-600);` |
| Texte | `text-rose` | `color: var(--cc-rose-500);` |
| Bordure | `border-gray-200` | `border-color: var(--cc-gray-200);` |
| Hover couleur | `hover-blue` | Fond bleu au survol + texte blanc |

## 4. Exemple HTML

```html
<div class="bg-blue text-white p-6 border-blue-600">
  <h3 class="text-white">Carte Bleue</h3>
  <p class="text-blue-100">Texte clair sur fond bleu.</p>
</div>
```
