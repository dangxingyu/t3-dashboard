# T³ research dashboard

Public, read-only summaries of the training-time testing research campaign.
The dashboard includes research questions, experiment progress, GPU purpose
counts, development learning/forgetting curves, accepted findings and plans.

`data.json` is a timestamped summary. No raw documents, training logs,
checkpoints, credentials, hostnames or server paths are published. A snapshot
older than fifteen minutes is labelled stale. Browser refresh cannot update
the underlying experiments.

Run locally with `python -m http.server 8766` and open `http://localhost:8766`.
Serve the repository root through GitHub Pages for the published dashboard.

Visual organization inspired by [Slow-Space Scaling](https://dangxingyu.github.io/slow-space-dashboard/).
