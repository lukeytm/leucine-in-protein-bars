# Leucine in protein bars

Leucine and protein figures for 16 protein bars, with collagen and on-sale status. Most brands don't print leucine, so this table shows which figures come from labels or brands and which are estimates.

Download [`leucine-in-protein-bars.csv`](leucine-in-protein-bars.csv). Or [filter and sort the table](https://lukeytm.github.io/leucine-in-protein-bars/). Further reading: [The 5 best high-leucine protein bars](https://medium.com/@luke5121/the-5-best-high-leucine-protein-bars-140e640971b2). Also on [Hugging Face](https://huggingface.co/datasets/Luketaplin/leucine-in-protein-bars).

## Who made this

This table is compiled by [Leucent](https://getleucent.com), which makes one of the bars listed, so we aren't neutral and our bar is listed first. Leucent 3.0 is in pre-production and not on sale, and its figures are our planned formula, not lab results.

## The bars at about 3 g or more

| Bar | Leucine | Protein | On sale |
|---|---|---|---|
| Leucent 3.0 | 3.0 g | 21 g | No |
| Pursuit Protein Bar | ~3.5 g (brand estimate) | 26.5 g | Yes |
| EVOBAR (EVO Sports Fuel) | 3.0–3.3 g | 20–23 g | Yes |
| Myprotein Loaded EAA Bar | 3.0 g | 15 g | Yes |
| ADDRA Labs Leucine-Boosted | ~2.9–3.2 g (part estimated) | 17–18 g | Yes |

The full 16 bars are in the CSV and at [leucine in popular protein bars](https://getleucent.com/high-leucine-protein-bars).

## Columns

- `leucine_g_min`, `leucine_g_max`: leucine per bar in grams. A single figure has the same min and max.
- `protein_g_min`, `protein_g_max`: protein per bar in grams.
- `leucine_basis`: where the leucine figure comes from.
- `contains_collagen`: `yes`, `no`, `by flavour`, `not listed` (not among the ingredients we checked) or `not stated`.
- `added_leucine`: whether the bar adds free leucine.
- `on_sale`: whether the bar is on sale, as far as we could tell.
- `source_url`: the page we used, where we have one.

## How the estimates work

Where a brand doesn't publish leucine, we estimate it from the protein grams and sources. Typical leucine shares are whey isolate 10–11%, milk protein and casein 9–10%, egg white 8.5%, soy isolate 8% and collagen or gelatin 3%. These are estimates, not lab results.

Figures were checked in October and November 2026, and formulas vary by flavour and country. If a brand publishes an amino acid profile, that number beats ours. Corrections are welcome as an issue.

This is general nutrition information, not medical advice.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit Leucent and link to this repository.
