# Energy-efficient-LLM
I utilized the PyTorch Profiler to perform an in-depth trace analysis, visualizing the execution timeline to pinpoint operations causing GPU idle states. Based on this, I designed DVFS strategies that dynamically lowered the GPU's voltage and frequency during these idle periods.
# Energy-Efficient LLM Trace Analysis

This repository contains analysis, code, and profiling workflows for our project on **Energy-Efficient Large Language Models (LLMs)**. We profiled a diverse range of LLM architectures, including:

- Encoder-only models (e.g., BERT)
- Decoder-only models (e.g., GPT series)
- Encoder-decoder models (e.g., T5)

Our work involves generating and analyzing trace files for each architecture using tools like **PyTorch Profiler** and **Holistic Trace Analysis** to identify GPU inefficiencies and opportunities for power optimization during idle and active phases.

## Trace File Availability

Due to GitHub's file size restrictions (limit: 100MB per file), we are **unable to upload the full trace files** (each approximately 430MB) directly to this repository.

If you're interested in accessing the complete trace datasets for reproduction or further analysis, please reach out via:

- GitHub Issues: Open a request with your use case
- Email: vaibhavreddyprf@gmail.com

We can share the files through alternative means (e.g., Google Drive, institutional storage, or direct links).

## Repository Contents

- 📁 `jupyter_notebooks_to_extract_traces`: Notebooks for power optimization insights and GPU activity visualization
- 📁 `traces_less_size`:  Profiling and trace parsing scripts
- 📄 `README.md`: You're here!
