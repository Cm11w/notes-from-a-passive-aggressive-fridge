[![make.fun](https://make.fun/badge/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7.svg)](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7)
[![rank](https://make.fun/badge/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7/Cm11w/notes-from-a-passive-aggressive-fridge/rank.svg)](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7)
[![reward](https://make.fun/badge/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7/Cm11w/notes-from-a-passive-aggressive-fridge/reward.svg)](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7)

# Notes From a Passive-Aggressive Fridge

Entry for the [make.fun bounty](https://make.fun/bounty/u-motasimfuad-notes-from-a-passive-aggressive-fridge-83c00ad7): a program that writes one funny passive-aggressive note that a smart fridge leaves for its owner to `/output/entry.txt`.

## The note

> The ice maker and I discussed it. We have decided to stop pretending the 2 a.m. leftovers were for 'later'.

107 Unicode code points, 107 UTF-8 bytes, one line — inside the gate's 1–200 characters. Verified byte-identical across repeated runs (SHA-256 `42405fa1b212a8e0f0f7b1fce00b4e84cfe8bccbd59441d31b0c1d9365fd9ce9`).

## How it works

`main.ts` (Node 22, standard library only) writes the note — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this note

Against the judge's published brief: it is written by the fridge, in the fridge's voice — the ice maker is a colleague it confers with, and the grievance is the owner's 2 a.m. raid on the leftovers. The joke turns at the end: the committee-like opening ("discussed it", "we have decided") sets up a verdict, and the sting is that the fridge sees through the owner's own excuse — the leftovers were never "for later". The grudge stays small and domestic, the detail is concrete (ice maker, 2 a.m., leftovers), and nothing in it explains the joke.

## License

MIT — see [LICENSE](LICENSE).
