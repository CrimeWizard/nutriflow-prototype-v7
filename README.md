# NutriFlow Prototype v7

**Pillar 3 — depth & habit** — reorder, search, favorites, staples. Built on v6 commerce + v5 weekly plan.

Egypt-first, for all budgets.

## Version map

| Version | Pillar | Focus |
|---------|--------|--------|
| v5 | 1 | Smart weekly plan (Sat–Fri), gym-aware meals |
| v6 | 2 | Honest checkout, cart control, orders persistence |
| **v7** | **3** | Reorder, search, favorites, staples |

## What's new in v7

| Feature | Detail |
|---------|--------|
| Order status | Mark delivered; Home "Current orders" uses status, not just time |
| Reorder | Full order or per-delivery from Orders; grocery reorder banner on Home |
| Search | Restaurants, meals, products, recipes (contextual, not a dead tab) |
| Favorites | Heart + Profile section; persists in `nf-v7-favorites` |
| Staples | Quick-add row on Groceries from history + defaults |
| Ingredients | Only shows products available at your selected supermarket |

## Run

```bash
npm install
npm run dev
```

Port: **5179**

## Demo flows

1. Place a grocery order → mark delivered → see reorder banner on Home
2. Heart a meal/recipe/product → check Profile → Favorites
3. Search "chicken" on Eat out or Groceries
4. Groceries → Your staples row after ordering
