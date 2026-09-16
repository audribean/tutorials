<div align="center">
    <h1><code>Error analysis tutorial</code></h1>
</div>

<h1>Environment</h1>

Note: The provided uv environment for running `error_analysis_tutorial.ipynb` assumes Category and Temporal Error Analysis are merged into pyannote.metrics. They are currently included as `pyannote.metrics.errors.{category_metrics,category_plots,temporal_metrics,temporal_plots}`

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
