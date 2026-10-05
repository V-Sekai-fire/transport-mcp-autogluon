# transport-mcp-autogluon

An Elixir Model Context Protocol server that exposes an automated machine learning library as tools for training, prediction and evaluation.

## What it is for

An agent calls its tools to fit tabular, multimodal and time-series predictors on a data file, predict with a trained model, and evaluate it on held-out data. The learning library runs in an embedded Python environment that the build installs. It serves over standard input and output by default, or over HTTP when configured.

## Build and run

```sh
mix deps.get
mix mcp.server
```

## Licence

MIT; see `LICENSE.md`.
