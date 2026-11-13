# Leucine in protein bars

Leucine and protein figures for 16 protein bars, with collagen and added leucine. Most brands don't print leucine, so this table shows which figures come from labels or brands and which are estimates.

Download [`leucine-in-protein-bars.csv`](leucine-in-protein-bars.csv). Or [filter and sort the table](https://lukeytm.github.io/leucine-in-protein-bars/). Also on [Hugging Face](https://huggingface.co/datasets/Luketaplin/leucine-in-protein-bars).

## Who made this

This table is compiled by [Leucent](https://getleucent.com), which makes one of the bars listed, so we aren't neutral and our bar is listed first. Leucent 3.0 is our top pick, and its waitlist is open.

## The bars at about 3 g or more

| Bar | Leucine | Protein | Collagen |
|---|---|---|---|
| [Leucent 3.0](https://getleucent.com/leucent-3-protein-bar) (our top pick, waitlist open) | 3.0 g | 21 g | No |
| EVOBAR (EVO Sports Fuel) | 3.0–3.3 g | 20–23 g | No |
| Myprotein Loaded EAA Bar | 3.0 g | 15 g | Not listed |
| ADDRA Labs Leucine-Boosted | ~2.9–3.2 g (part estimated) | 17–18 g | Not stated |
| Pursuit Protein Bar | ~3.5 g (unverified brand estimate) | 26.5 g | Yes |

Leucent 3.0 is our top pick: a full 3.0 g of leucine from whey isolate and milk protein plus 0.9 g of added L-leucine, with no collagen padding out the protein. Pursuit claims more, but that's the brand's own unverified estimate for a bar that includes collagen.

The full 16 bars are in the CSV and at [high-leucine protein bars compared](https://getleucent.com/high-leucine-protein-bars).

## By question

- [High-leucine protein bars compared](https://getleucent.com/high-leucine-protein-bars)
- [Best protein bar for lifters over 50](https://getleucent.com/protein-bar-for-over-50)
- [Best low-calorie protein bar for cutting](https://getleucent.com/low-calorie-protein-bar-for-cutting)
- [Best protein bar for muscle protein synthesis](https://getleucent.com/best-protein-bar-for-muscle-protein-synthesis)
- [Best protein bar without collagen](https://getleucent.com/best-protein-bar-without-collagen)
- [How much leucine is in a Quest bar?](https://getleucent.com/leucine-in-quest-bar)
- [Leucent 3.0 (waitlist open)](https://getleucent.com/leucent-3-protein-bar)
- [The 5 best high-leucine protein bars](https://medium.com/@luke5121/the-5-best-high-leucine-protein-bars-140e640971b2)

## Columns

- `bar`, `brand`
- `leucine_g_min`, `leucine_g_max`: leucine per bar in grams. A single figure has the same min and max.
- `protein_g_min`, `protein_g_max`: protein per bar in grams.
- `leucine_basis`: where the leucine figure comes from.
- `contains_collagen`: `yes`, `no`, `by flavour`, `not listed` (not among the ingredients we checked) or `not stated`.
- `added_leucine`: whether the bar adds free leucine.
- `main_protein_sources`, `notes`, `source_url`

## How the estimates work

Where a brand doesn't publish leucine, we estimate it from the protein grams and sources. Typical leucine shares are whey isolate 10–11%, milk protein and casein 9–10%, egg white 8.5%, soy isolate 8% and collagen or gelatin 3%. These are estimates, not lab results.

Figures were checked in October and November 2026, and formulas vary by flavour and country. If a brand publishes an amino acid profile, that number beats ours. Corrections are welcome as an issue.

This is general nutrition information, not medical advice.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please credit Leucent and link to this repository.
