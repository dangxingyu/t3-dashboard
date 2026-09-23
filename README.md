# T³ research dashboard

Public, read-only summaries of the training-time testing research campaign.
The dashboard includes research questions, experiment progress, GPU purpose
counts, development learning/forgetting curves, accepted findings and plans.

`data.json` is a timestamped summary, published every fifteen minutes. No raw documents, training logs,
checkpoints, credentials, hostnames or server paths are published. A snapshot
older than forty-five minutes is labelled stale. Browser refresh cannot update
the underlying experiments.

Run locally with `python -m http.server 8766` and open `http://localhost:8766`.
Serve the repository root through GitHub Pages for the published dashboard.

Visual organization inspired by [Slow-Space Scaling](https://dangxingyu.github.io/slow-space-dashboard/).

The complete 56-case CPT development and external-evaluation figures are public
summary plots. The external figure includes every endpoint and all 32 adaptation
contrasts, with document intervals and explicit single-seed/exploratory limits.
