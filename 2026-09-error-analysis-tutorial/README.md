<div align="center">
    <h1><code>Error analysis tutorial</code></h1>
</div>

This tutorial walks through `pyannote.metrics`'s error analysis tools for speaker diarization: `CategoryStats` and `CategoryErrorAnalysis` for breaking down errors by categorical speaker traits (e.g. gender, accent), and `TemporalErrorAnalysis` for breaking them down by a time-series signal (e.g. SNR, reverb), plus the plotting helpers for both.

<h1>Environment</h1>

You can reproduce this environment in four simple steps:

1. Install [uv](https://docs.astral.sh/uv/getting-started/installation/) (v0.11 or newer)

2. Put `pyproject.toml`, `uv.lock`, and `error_analysis_tutorial.ipynb` in the same directory

3. From that directory, sync the environment

   ```bash
   uv sync
   ```

4. Launch the notebook

   ```bash
   uv run jupyter notebook error_analysis_tutorial.ipynb
   ```

   (or `uv run jupyter lab error_analysis_tutorial.ipynb`)
