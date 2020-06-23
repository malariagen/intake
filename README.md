# Intake data catalogs for MalariaGEN

This repository hosts [intake](https://intake.readthedocs.io/) data
catalogs for accessing data resources published by
[MalariaGEN](https://www.malariagen.net).

The catalog for data on Google Cloud Storage is located at
`https://malariagen.github.io/intake/gcs.yml`. To open this catalog:

```python
import intake

cat = intake.open_catalog('https://malariagen.github.io/intake/gcs.yml')
```

**Please note that data included in these catalogs are made available
prior to publication and subject to terms of use.**

Data from the ag2 and ag3 catalogs are released by the [Anopheles
gambiae 1000 Genomes
Consortium](https://www.malariagen.net/projects/ag1000g) and are
subject to the [Ag1000G terms of
use](https://www.malariagen.net/data/terms-use/ag1000g-terms-use).

Data from all other catalogs are released jointly by the Wellcome
Sanger Institute Malaria Programme and their research partners. These
data have been released prior to publication. Analyses of these data
are ongoing and a publication is in preparation. It is not permitted
to use the data for publication, i.e., any type of communication with
the general public.