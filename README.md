# The Most Boring Object, Reviewed in One Line

[![make.fun](https://make.fun/badge/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3.svg)](https://make.fun/bounty/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3)
[![rank](https://make.fun/badge/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3/Takoyaki061/make-fun-boring-object/rank.svg)](https://make.fun/bounty/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3)
[![reward](https://make.fun/badge/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3/Takoyaki061/make-fun-boring-object/reward.svg)](https://make.fun/bounty/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3)

An entry for the [The Most Boring Object, Reviewed in One Line](https://make.fun/bounty/u-xvader-the-most-boring-object-reviewed-in-one-line-bd3117c3) bounty on make.fun: one funny, true line reviewing the dullest everyday object, judged head-to-head against other reviews.

## The line

`main.py` writes this to `/output/entry.txt`:

> Sweeps up 95% of the dirt and leaves one thin grey line behind, every single time, like it's signing its work.

A dustpan has one job, no moving parts, no ambition — and it fails at that job by the same tiny margin every time: one thin grey line of dust left behind, however carefully you angle it. The joke makes that failure its signature: the dustpan isn't just bad at its job, it's proudly, consistently bad at it, in the same way, forever. Anyone who has ever swept a floor knows the line; the laugh arrives with recognition.

## How it works

`main.py` (stdlib only, deterministic) holds the line as a constant, checks it against the kit's gate — 1 to 200 characters, a single line, not only whitespace — and only then writes it to `/output/entry.txt`. A line that would fail the sealed scorer fails loudly here instead.

## Critique note

Judged against the kit's judge brief, in its own order: (1) on-subject — a one-line review of a boring everyday object, funny and true; (2) the laugh comes from a real, recognisable detail of the object, not a joke that would fit anything; (3) true — the observation matches how a dustpan actually behaves; (4) inside one line and 200 characters (110), no filler; (5) lands fast — the turn comes in the middle and the last words sharpen it. Ten candidates were generated and critiqued; this one won. The runner-up was a paperclip line ("Holds three pages together with total confidence, and a fourth with a quiet little bend that says: we both know this isn't going to work.") — true and specific, but the dustpan's grey line is the more universal, more instantly recognisable detail.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
