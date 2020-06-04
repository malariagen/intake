# Intake data catalogs for MalariaGEN

This repository hosts intake data catalogs for accessing data resources published by [MalariaGEN](https://www.malariagen.net).

The catalog for data on Google Cloud Storage is located at https://malariagen.github.io/intake/gcs.yml. To open this catalog:

```python
import intake

cat = intake.open_catalog('https://malariagen.github.io/intake/gcs.yml')
```
