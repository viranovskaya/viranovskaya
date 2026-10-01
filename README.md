# Hi, I'm Daria

I am a scientific Python developer and computational neuroscience researcher. I build tested research software for neurodata, time-series analysis, model evaluation, and reproducible scientific workflows.

I work on problems where numerical correctness, data provenance, validation, and clear reporting matter. My background includes EEG and sleep research, experimental design, statistics, and computational neuroscience.

I am available for remote scientific Python and research-software work, and for research software, research assistant, predoctoral, and PhD roles in Vienna.

## Selected work

- [**NeuroData Release Security Audit**](https://github.com/viranovskaya/neurodata-release-security-audit) — a local audit that leaves source datasets unchanged while reporting on privacy-relevant metadata, archive structure, broken references, and scan integrity before release. Current prerelease: [`v0.3.0b3`](https://github.com/viranovskaya/neurodata-release-security-audit/releases/tag/v0.3.0b3).
- [**Sleep-EEG staging evaluation**](https://github.com/viranovskaya/sleep-eeg-staging-evaluation) — external evaluation of YASA across 20 Sleep-EDF recordings and 28,259 aligned epochs, with recording-level uncertainty and stage-specific error analysis. Current release: [`v0.3.1`](https://github.com/viranovskaya/sleep-eeg-staging-evaluation/releases/tag/v0.3.1) · [Zenodo DOI](https://doi.org/10.5281/zenodo.21354517).
- [**Dense-EEG stop-signal pipeline**](https://github.com/viranovskaya/dense-eeg-stop-signal-pipeline) — traceable QC, event reconstruction, reviewed ICA, and provenance for 129-channel stop-signal EEG, with a separate 127-EEG-channel synthetic benchmark. Current release: [`v0.3.0`](https://github.com/viranovskaya/dense-eeg-stop-signal-pipeline/releases/tag/v0.3.0).

Additional work includes [tested neural-dynamics simulations](https://github.com/viranovskaya/neural-dynamics-models) and a [privacy-safe OpenSesame visual-world demonstration](https://github.com/viranovskaya/opensesame-visual-world-demo).

## Open-source contributions

I contribute focused fixes, tests, validation rules, and documentation to scientific Python and neuroinformatics projects. As of 1 October 2026, 24 of my pull requests have been merged across 10 external repositories. Selected merged contributions:

- **HED and BIDS:** source-preserving sleep-annotation benchmarks with [synthetic fixtures](https://github.com/hed-standard/hed-benchmarks/pull/3) and [real BOAS annotations](https://github.com/hed-standard/hed-benchmarks/pull/4), schema checks for [behavioural timing columns](https://github.com/bids-standard/bids-specification/pull/2467) and [BrainVision file triplets](https://github.com/bids-standard/bids-specification/pull/2501), and a [PyBIDS indexing fix](https://github.com/bids-standard/pybids/pull/1273).
- **Pynapple:** [IntervalSet support for event-triggered averages](https://github.com/pynapple-org/pynapple/pull/639), fixes for [ISI histograms with constant intervals](https://github.com/pynapple-org/pynapple/pull/656) and [failed tutorial downloads](https://github.com/pynapple-org/pynapple/pull/657).
- **MNE ecosystem:** experimental [Array API support for ReceptiveField with compatible estimators, including PyTorch inputs, and corrected inverse-pattern axis ordering for multiple outputs](https://github.com/mne-tools/mne-python/pull/14327), [CUDA-backed Hilbert transforms](https://github.com/mne-tools/mne-python/pull/14164), [correct paths for nested BIDS datasets](https://github.com/mne-tools/mne-bids/pull/1637), [rest-epoch validation](https://github.com/mne-tools/mne-bids-pipeline/pull/1272), [decoding safeguards](https://github.com/mne-tools/mne-bids-pipeline/pull/1284), and [OpenBLAS thread-tuning documentation](https://github.com/mne-tools/mne-python/pull/14064).
- **EEGLAB interoperability:** [importing epoched files without event metadata](https://github.com/mne-tools/mne-python/pull/14163) and correcting event mapping after dropped epochs in [MNE](https://github.com/mne-tools/mne-python/pull/14067) and [eeglabio](https://github.com/jackz314/eeglabio/pull/26).
- **SleepECG:** [validation and documentation for external actigraphy inputs](https://github.com/cbrnr/sleepecg/pull/315), a [searchback correction](https://github.com/cbrnr/sleepecg/pull/319), and a [CAP Sleep Database reader](https://github.com/cbrnr/sleepecg/pull/321).

Open work includes [lagged cross-correlation in Pynapple](https://github.com/pynapple-org/pynapple/pull/640) and [parallel manual and automated sleep annotations in BIDS/HED](https://github.com/bids-standard/bids-examples/pull/560). See my [GitHub contribution history](https://github.com/search?q=author%3Aviranovskaya+is%3Apr&type=pullrequests) for the full list.

## Technical focus

**Python:** NumPy, pandas, SciPy, scikit-learn, PyTorch, pytest, GitHub Actions, numerical validation, model evaluation, and reproducible data pipelines.

**Neuroinformatics:** MNE, MATLAB/EEGLAB, BIDS/HED, EEG quality control, sleep staging, event reconstruction, provenance, and metadata review.

[ORCID](https://orcid.org/0009-0009-3819-9362) · [LinkedIn](https://www.linkedin.com/in/agafonova-neuro/) · [Email](mailto:agafonovadaria97@gmail.com)
