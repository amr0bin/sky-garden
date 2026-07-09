# Sky Garden · Spéirghairdín

*A balcony garden in the Vancouver sky, grown in pots and tended season by season — carrying a thread of Irish and wider Celtic plant tradition into a new place.*

This is my living record of the container garden on my balcony — **twenty feet by five**, with a north-eastern aspect and full sun for most of the day, here in Vancouver (a mild coastal climate, roughly USDA zone 8b). I've gathered medicinal and heritage plants that thrive in pots, that feed the birds, bees, and butterflies who visit, and that connect me back to home. I'm building it to grow gradually, so that there is always something alive and working out there, in every season of the year.

*From spéir (sky) and gairdín (garden) — an offered compound, in the spirit of the place.*

---

## The interactive tour

I open **[`index.html`](index.html)** in any browser to explore the garden two ways. The **garden plan** is a to-scale map: I select any plant to see its botanical illustration and read its medicinal uses, how I prepare it, what it needs from me, and the story it carries — and I filter by season to see what will be awake at any point in the year. The **harvest calendar** shows, month by month, what to gather and make across all twenty plants, and highlights what's ready in the current month. Each plant has an original line illustration; I can replace any of these with my own photograph by dropping a file into [`images/`](images/) (see that folder's note).

To publish it online for free, enable **GitHub Pages** (Settings → Pages → Deploy from branch → `main` / root). The tour will then be live at `https://<your-username>.github.io/sky-garden/`.

---

## The collection

Twenty plants — a balance of small trees and shrubs for structure and the birds, and herbs and flowers for medicine and the pollinators. Every one is container-suitable, and each carries either an Irish name, a piece of Celtic lore, or both. In the tour, each also has its own botanical illustration and a place in the harvest calendar.

| Plant | Gaeilge | Botanical | Role |
|---|---|---|---|
| Crab Apple 'Dolgo' | Crann Úll Fiáin | *Malus* 'Dolgo' | Anchor tree · pollinator · pectin |
| Blackthorn (Sloe) | Draighean | *Prunus spinosa* | Protection · sloes · earliest bloom |
| Hawthorn (Whitethorn) | Sceach Gheal | *Crataegus monogyna* | Heart tonic · the fairy tree |
| Elder | Trom | *Sambucus nigra* | Flower & berry · immune |
| Rowan | Caorthann | *Sorbus aucuparia* | Protection · winter berries |
| Foxglove *(admire only)* | Lus Mór | *Digitalis purpurea* | Heritage & bees · **toxic** |
| Heather (Ling) | Fraoch | *Calluna vulgaris* | Evergreen · late forage · home |
| Yarrow | Lus na Fola | *Achillea millefolium* | Wound herb · pollinators |
| Meadowsweet | Airgead Luachra | *Filipendula ulmaria* | Druid herb · pain & fever |
| Vervain | — | *Verbena officinalis* | Druid herb · nervine · calm |
| Water-mint | Cartlainn | *Mentha aquatica* | Druid herb · digestive |
| Valerian | — | *Valeriana officinalis* | Calm · sleep · the bee charm |
| St John's Wort | Lus Cholm Cille | *Hypericum perforatum* | Midsummer oil · mood |
| Nettle | Neantóg | *Urtica dioica* | Spring tonic · butterfly host |
| Calendula (Pot Marigold) | — | *Calendula officinalis* | The salve flower |
| Chamomile | — | *Chamaemelum nobile* | Calm · sleep · the bee charm |
| Primrose | Sabhaircín | *Primula vulgaris* | Fairy flower · earliest nectar |
| Comfrey | Lus na gCnámh Briste | *Symphytum officinale* | Knitbone · topical only |
| Lemon Balm | — | *Melissa officinalis* | Gladness · the bee herb |
| Wild Garlic (Ramsons) | Creamh | *Allium ursinum* | Spring green · shade-lover |

Meadowsweet, vervain, and water-mint together are the three herbs the Druids held most sacred. Full records for each plant — with the folklore sources behind them, and harvest timings — live in [`data/plants.json`](data/plants.json), which also feeds the tour.

---

## The guides

- **[Seasonal plan](docs/seasonal-plan.md)** — how to build the garden gradually, season by season, so there is always activity.
- **[Pollinators & bees](docs/pollinators-and-bees.md)** — welcoming birds, bees, and butterflies, and an honest look at keeping a hive on a balcony in Vancouver.
- **[Preparation guide](docs/preparation-guide.md)** — how to turn the harvest into teas, oils, salves, and syrups, safely.

---

## Repository structure

```
sky-garden/
├── index.html                     the interactive tour (garden plan + harvest calendar)
├── data/
│   └── plants.json                the plant records (the tour reads from a copy of these)
├── images/                        drop my own plant photos here (optional)
│   └── README.md
├── docs/
│   ├── seasonal-plan.md
│   ├── pollinators-and-bees.md
│   └── preparation-guide.md
├── README.md
└── LICENSE
```

---

## A note on safety

These are traditional and herbal uses I've gathered for interest and heritage. **This is not medical advice.** Correct plant identification is essential; several of these plants have real cautions or interactions with medication; and one — foxglove — is here for its lore and its bees only, and must never be taken internally. Before I prepare anything for myself or a guest, I cross-check a reputable herbal reference or a qualified practitioner, and I patch-test any topical preparation first.

## A note on heritage

I've drawn the Irish (Gaeilge) names and folklore from Irish plant-lore sources, and included them only where I could reasonably verify them; where I haven't yet found a confident name, I've left it open. I mean to correct and add to it over time — a record that grows alongside my garden and my own knowledge.
