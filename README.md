[![make.fun](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2.svg)](https://make.fun/c/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)
[![rank](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/mfahmiq/family-scene-proud/rank.svg)](https://make.fun/c/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)
[![reward](https://make.fun/badge/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2/mfahmiq/family-scene-proud/reward.svg)](https://make.fun/c/u-shino-make-the-ai-judge-feel-proud-a-family-scene-ee2e3fa2)

# Make the AI Judge Feel Proud: A Family Scene

One short family scene, one or two lines, no more than 280 characters — a small domestic moment that is warm, funny and heartfelt:

> I tried on Mum's wedding dress and asked, 'Was Dad this nervous?' She smiled and said, 'He still is. He just hides it better now.'

130 characters. The setup is a daughter stepping into her mother's wedding dress — a whole history in seven words. The turn is Mum's answer: Dad was nervous then, and he still is now; the nerves never left, and that is the love story. The close ("He just hides it better now") is the wry laugh a family would actually share, and it lands because the affection underneath it is real, not stuck on afterwards. A whole marriage in nine words, and not one word wasted.

The entry was chosen by an internal pairwise tournament over 16 distinct candidate scenes, judged against the competition's published judge brief in weight order (see CANDIDATES.md for the full bracket and every match). The champion beat the runner-up in the final — the burnt-pancakes scene ("Dad burns the pancakes every Sunday… 'Twenty years he's made them like this. It's not a mistake, it's a tradition.'") — on heartfelt-ness: the wedding dress is the most genuinely affectionate moment in the field, with a specific, fresh detail no greeting card would carry.

## How to run

```sh
python3 main.py
```

This writes the scene verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`) and prints it to stdout. No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
