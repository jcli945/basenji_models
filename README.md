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
```

Each species directory contains the checkpoint files for the best trained model.

Usage

Please restore the TensorFlow checkpoint files together:

checkpoint
model_best.tf.data-00000-of-00001
model_best.tf.index
model_best.tf.meta

Parameter and sample description files are provided in the repository root directory.

Notes

Large model files and HIS-element archives are tracked with Git LFS. To download the actual files rather than LFS pointer files, please install Git LFS, clone the repository, and run git lfs pull.

# HIS-element assets

Genome-wide HIS-element annotations for five grass species are available in the `HIS-element_assets` directory:  
[HIS-element_assets](https://github.com/jcli945/basenji_models/tree/main/HIS-element_assets)

This directory contains tissue-level BED files of HIS-elements for each species, together with a detailed usage guide.  
For rice, please note that the HIS-element BED files use the **MSU7.0** coordinate system.
