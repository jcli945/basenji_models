# Basenji models for six grass genomes

This repository provides trained Basenji model files, parameter files, and sample description files for six grass genomes:

- Bdistachyon
- MH63
- Sitalica
- Sorghum
- Zmays
- ZS97

## Repository contents

For each species, the corresponding directory contains the best trained model checkpoint:

- `checkpoint`
- `model_best.tf.data-00000-of-00001`
- `model_best.tf.index`
- `model_best.tf.meta`

The root directory also includes:

- `*_params.txt`: model/training parameter settings
- `*_samples.txt`: sample information used for model construction

## Directory structure

```text
Bdistachyon/
MH63/
Sitalica/
Sorghum/
Zmays/
ZS97/

Each species directory contains the checkpoint files for the best trained model.

Usage

Please restore the TensorFlow checkpoint files together:

checkpoint
model_best.tf.data-00000-of-00001
model_best.tf.index
model_best.tf.meta

Parameter and sample description files are provided in the repository root directory.

Notes

Large model files are managed using Git LFS.
