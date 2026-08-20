# portable_EEG

> **Status: archived historical prototype**

This repository contains exploratory Python scripts developed in 2024 for
auditory oddball / P300 ERP processing with portable EEG recordings from
Muse and Neurosity devices.

## Contents

- `muse_v10.py` — early Muse auditory-oddball ERP analysis.
- `code_neurosity-muse.py` — exploratory comparison workflow for Muse and
  Neurosity recordings using MNE-Python.

The scripts reconstruct stimulus events from timestamps, create MNE EEG
objects, apply band-pass filtering, epoch standard and deviant trials, and
calculate condition-average ERPs.

## Important limitations

This repository is preserved for historical and portfolio provenance only.

It is **not a reproducible scientific analysis package**:

- the original EEG recordings and task JSON files are not included;
- input filenames and directory layouts are hard-coded;
- software versions and a reproducible environment were not recorded;
- there are no automated tests;
- no validated reference outputs are included;
- artifact rejection and EEG quality-control procedures are incomplete;
- statistical inference was not implemented as a validated group analysis;
- some historical plots/CSV outputs use MNE data stored internally in volts
  while labels refer to microvolts, so numerical amplitudes from these
  scripts should not be treated as validated final results.

No scientific conclusions should be drawn from this repository alone.

## Historical context

The code is retained to document early work with portable EEG acquisition
and auditory oddball paradigms. It is no longer actively maintained.
