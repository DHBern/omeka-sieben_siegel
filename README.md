# omeka-sieben_siegel

Static archive of the Omeka S site(s) **Sieben Siegel 2022**, formerly at:

- `https://omeka.unibe.ch/s/sieben_siegel` → https://dhbern.github.io/omeka-sieben_siegel/s/sieben_siegel/
- `https://omeka.unibe.ch/s/sieben_siegel` → https://dhbern.github.io/omeka-sieben_siegel/s/sieben_siegel/

- Snapshot: 2026-11-24, exported with `tools/export_site.py` from [DHBern/omeka-admin](https://github.com/DHBern/omeka-admin).
- Paths are kept as in Omeka (`/s/<slug>/page/…`, `/item/…`, `/media/…`, `/item-set/…`), so old URLs are forwarded 1:1.
- Images are served from the `large` derivatives; non-image originals up to 25 MB are included. Search, filters and login are disabled.
- Larger originals are not included; they are listed in `_export/large_files.tsv` and remain in the v3 archive.
