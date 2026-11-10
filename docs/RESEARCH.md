# Research approach

This document describes the project's evaluation principles. It is not an executable protocol or a claim that a public benchmark has been completed.

## Chronology and information availability

A historical row can contain information recorded after a game. Final scores, season totals, and postgame statistics must not enter the same game's prediction features. Suspended games and later corrections require explicit assumptions about when results became available. A game-start date alone is not proof of pregame publication time.

Evaluation should replay decisions in order, with predictions made before eligible result updates. Any use of prior seasons, franchise identity mappings, or same-day ordering must be recorded in the protocol.

## Comparisons and reporting

Simple constant-probability and historical-frequency baselines help establish whether a more complex model adds value. Team-strength approaches such as Elo and Log5 are part of the research background; this release supplies no implementation or selected public model.

Comparisons should use matching game identifiers and eligibility rules. Brier score and log loss evaluate probability forecasts. Hard-pick accuracy needs its picked-game denominator and an explicit rule for probabilities of exactly 0.5. Excluded games, ties, missing results, and abstentions should remain visible in coverage reporting.

## Interpretation limits

Retrospective reconstruction is distinct from predictions saved before real games. Prior exposure to an evaluation period prevents describing that period as a fresh untouched holdout. Archive hashes establish byte integrity, not the authenticity or historical availability of a source.

This public release contains no performance figures, evaluation ledgers, or evidence supporting live accuracy, calibration, superiority over other models, or financial returns.
