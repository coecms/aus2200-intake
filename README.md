# AUS2200 simulations Intake Catalogue

## Usage

The catalogue is available in intake's default catalogue list in the CLEX Conda
environment

```python
import intake

 cat = intake.open_catalog('/g/data/ua8/Working/packages/aus2200-intake/catalogue.yaml') 
```

Individual datasets are catalogued using intake-esm

## Admin

This catalogue exists on Gadi's NCI filesystem under /g/data/hh5/public/apps/aus2200-intake

Use `git pull` to download changes from Github

Catalogue csv listings themselves need to be generated, they are not in the
repository due to their size. This may be done by running `make` within the
directory

The intake data package is under the directory `package/`, it simply provides
an intake entry point pointing to the catalogue directory


More information is available in the official [intake-esm](https://intake-esm.readthedocs.io/en/latest/) documentation.

See the demo notebook for examples of how to use it.
