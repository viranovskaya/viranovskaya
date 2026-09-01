# Hi, I'm Daria

I am a scientific Python developer and computational neuroscience researcher. I build tested data pipelines, ML evaluation workflows, and reproducible research software for complex time-series and neurodata.

My work combines software delivery with research practice: reproducing difficult bugs, turning analysis code into maintainable packages, implementing validation and quality-control workflows, and documenting the assumptions behind numerical results. I have a Master's degree in Psychology with Distinction from HSE University's Cognitive Sciences and Technologies programme, with training in EEG/ERP methods, neuroimaging, neural modelling, statistics, and experimental design.

I am available for remote contract and part-time work in scientific Python, ML evaluation, research software, and data pipelines. I am also open to research software, research-assistant, predoctoral, and PhD roles in Vienna.

## What I can help with

- **Scientific Python and research software** — refactoring notebooks and scripts into tested packages, command-line tools, and reproducible workflows.
- **ML and model evaluation** — data alignment, validation design, appropriate metrics, error analysis, uncertainty reporting, and regression tests.
- **Data pipelines and quality control** — time-series processing, structured metadata, traceable decisions, provenance, and automated reports.
- **Debugging and upstream contributions** — minimal reproductions, numerical and API-safe fixes, focused tests, CI, and technical documentation.

## Selected work

- [NeuroData Release Security Audit](https://github.com/viranovskaya/neurodata-release-security-audit) — local, read-only checks of privacy-relevant metadata, file coverage, references, and integrity in neurodata release candidates; current prerelease: [`v0.3.0b1`](https://github.com/viranovskaya/neurodata-release-security-audit/releases/tag/v0.3.0b1), with a local browser interface for reviewing audit results without uploading data.
- [Sleep-EEG staging evaluation](https://github.com/viranovskaya/sleep-eeg-staging-evaluation) — external evaluation of YASA on 20 Sleep-EDF recordings and 28,259 aligned epochs; current release: [`v0.3.1`](https://github.com/viranovskaya/sleep-eeg-staging-evaluation/releases/tag/v0.3.1) with a [Zenodo DOI](https://doi.org/10.5281/zenodo.21354517).
- [Dense-EEG stop-signal pipeline](https://github.com/viranovskaya/dense-eeg-stop-signal-pipeline) — traceable QC, event reconstruction, reviewed ICA, provenance, and synthetic benchmarking for 129-channel stop-signal EEG; current release: [`v0.3.0`](https://github.com/viranovskaya/dense-eeg-stop-signal-pipeline/releases/tag/v0.3.0).
- [Neural dynamics models](https://github.com/viranovskaya/neural-dynamics-models) — tested simulations of equilibrium potentials, conductance dynamics, spiking networks, and graph topology; current release: [`v0.1.0`](https://github.com/viranovskaya/neural-dynamics-models/releases/tag/v0.1.0).
- [OpenSesame visual-world demo](https://github.com/viranovskaya/opensesame-visual-world-demo) — an eight-trial auditory visual-world software demonstration using generated stimuli; current release: [`v1.0.0`](https://github.com/viranovskaya/opensesame-visual-world-demo/releases/tag/v1.0.0).

## Selected upstream contributions

**Merged**

- BIDS schema checks for [behavioural files with onset and duration](https://github.com/bids-standard/bids-specification/pull/2467) and [complete BrainVision file triplets](https://github.com/bids-standard/bids-specification/pull/2501).
- A [PyBIDS indexing fix](https://github.com/bids-standard/pybids/pull/1273) that keeps entity parsing within the dataset root instead of matching entity-like parent directories.
- MNE-Python contributions covering [CUDA-backed Hilbert transforms](https://github.com/mne-tools/mne-python/pull/14164), [epoched EEGLAB files without events](https://github.com/mne-tools/mne-python/pull/14163), [OpenBLAS threads](https://github.com/mne-tools/mne-python/pull/14064), and [docstring parameter types](https://github.com/mne-tools/mne-python/pull/14100).
- MNE-BIDS ecosystem validation for [tracking-system metadata](https://github.com/mne-tools/mne-bids/pull/1636), [rest epochs](https://github.com/mne-tools/mne-bids-pipeline/pull/1272), [nested BIDS roots](https://github.com/mne-tools/mne-bids/pull/1637), and [decoding with too few epochs](https://github.com/mne-tools/mne-bids-pipeline/pull/1284).
- SleepECG contributions covering [external actigraphy inputs](https://github.com/cbrnr/sleepecg/pull/315), [repeated searchback scans in unusable ECG segments](https://github.com/cbrnr/sleepecg/pull/319), and a [CAP Sleep Database reader](https://github.com/cbrnr/sleepecg/pull/321).

**Open**

- [Parallel manual and automated sleep-stage annotations in BIDS/HED](https://github.com/bids-standard/bids-examples/pull/560).

## Technical focus

**Core:** Python, NumPy, pandas, SciPy, pytest, GitHub Actions, numerical validation, time-series analysis, reproducible pipelines, and research software testing.

**Scientific domains:** MNE, MATLAB/EEGLAB, BIDS/HED, EEG quality control, sleep staging, metadata review, event reconstruction, experimental software, and computational-neuroscience models.

[ORCID](https://orcid.org/0009-0009-3819-9362) · [LinkedIn](https://www.linkedin.com/in/agafonova-neuro/) · [Email](mailto:agafonovadaria97@gmail.com)
