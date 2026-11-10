# MLB Predictor

Research into historical Major League Baseball game-outcome forecasting, with an emphasis on chronological evaluation, data provenance, and clear reporting of uncertainty.

**Status: early research prototype · documentation-only public release.** This repository introduces the project and its research standards. It does not currently contain a runnable application, model implementation, dataset, trained weights, or published performance results.

## Project scope

The project explores how simple statistical baselines and team-strength models can be evaluated against historical baseball outcomes. The underlying work includes offline historical replay and a private interface for inspecting saved evaluation records. Those research artifacts have not been packaged for public use.

The intended prediction target is a game's winning team and its win probability. Historical analysis does not establish prospective forecasting performance. No live schedule, current-season predictions, betting recommendations, or profitability claims are provided here.

## Research standards

- Use information available before the prediction decision; keep outcome fields separate from predictive inputs.
- Separate training, development, and retrospective evaluation periods. Document any previously observed evaluation data.
- Compare candidate models with simple baselines on the same eligible games.
- Report probability quality alongside hard-pick accuracy, including denominators, exclusions, and abstentions.
- Record source versions, transformations, assumptions about result availability, and reproducibility limits.

This initial README records the project’s evaluation principles and public release boundaries. Supporting research and contribution documentation will be added through the reviewed pull-request workflow.

## Availability

There are no installation or execution steps for this release. The private implementation depends on environment-specific tooling and private evaluation files. Portable dependencies, data redistribution, and a distributable example still require review before code can be offered. There is no public demo or deployment associated with this repository.

## Included in this initial commit

- This project overview, maturity statement and release boundaries.
- Research standards, data-source references and feedback guidance.

No installation, dependency configuration or application test commands apply to this documentation-only commit.

## Data sources and rights

Historical research has considered [Retrosheet game logs](https://www.retrosheet.org/gamelogs/index.html) and [Chadwick Baseball Bureau's retrosplits](https://github.com/chadwickbureau/retrosplits). These links identify external resources; this release redistributes none of their datasets or source files.

The retrosplits publisher declares ODbL 1.0 for its database and DbCL 1.0 for individual contents, with underlying Retrosheet attribution. Each source has its own terms and provenance requirements; inclusion in historical research does not transfer those rights to this repository. Consult the publishers' current notices before using their material.

No open-source license grant is included in this initial release. Third-party materials remain subject to their respective terms.

## Feedback

Documentation corrections and methodological questions are welcome through GitHub issues. Please describe the relevant assumption or passage and provide a public reference where possible. Do not attach credentials, personal information, private evaluation artifacts or third-party datasets. Link to a publisher’s official source and discuss rights before proposing substantial code or data.

This is an independent research project and is not affiliated with or endorsed by Major League Baseball, Retrosheet, or Chadwick Baseball Bureau.
