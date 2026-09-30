# September 30, 2026 live-source preservation capture

Source catalog: https://490d.com/knowledge-catalog/  
Canonical source index: https://490d.com/source/490d-unified-chronology/  
Matching Internet Archive deposit: https://archive.org/details/490d-unified-chronology-live-source-2026-09-30

## Scope and integrity

The repository contains all 83 original files directly listed by the canonical source index at capture: 76 research Markdown files through File_70 and Supplement A, four active control Markdown files, the non-controlling Repository Change Archive, and Publication Manifest v29 in CSV and XLSX. Their bytes match the original preservation inventory. The linked Judah-kings chart HTML, original index and sitemap, and historical v28 manifests are also retained unchanged. Earlier repository files, historical manifests, Git history, and the July release/tag are retained.

`source-inventory.json`, `related-inventory.json`, and `additional-inventory.json` are unchanged inventories from the matching Internet Archive preservation package. Their `path` values refer to that package layout; they also describe some files present only in that larger package. `repository-inventory.json` maps the materials mirrored here to repository-relative paths. `SHA256SUMS.txt` covers these 88 mirrored source files, including the source index and sitemap, and uses paths relative to the repository root. From that root, verify with `sha256sum -c preservation/2026-09-30/SHA256SUMS.txt`.

## Capture date and source revisions

September 30, 2026 is the retrieval/capture date, not a new editorial edition or a shared revision date. The live controls identify Restart Capsule v11.54 (September 13 pre-pro canonical refresh), State Vocabulary Register v1.55, Style Guide v2.5, and Project Procedures v3.5. The historical Change Archive identifies v1.57, September 6. Publication Manifest v29 retains older September 6 control-version pointers and pending-deposit language. These inconsistencies and older archive links in the original index are preserved verbatim rather than silently corrected. The live canonical Markdown controls interpretation; archived copies and the Change Archive are preservation/history layers.

## Boundaries and known unavailable links

The current lowercase, hyphenated File_70 Supplement A filename from the live index is included. The alternate underscore-style Supplement A URL in the sitemap returned HTTP 404 during capture. File_65's referenced `File_65.Figure_01.Kings_of_Judah_Actual_vs_Verbatim.jpg` also returned HTTP 404; no image has been substituted. Directory listing requests for archive/, control/, and manifest/ returned HTTP 403, so unlinked historical versions were not enumerated.

The unchanged chart HTML references external Chart.js 4.4.1 from a CDN. The JavaScript library is third-party MIT-licensed software and is not copied into this repository or relabeled under the corpus license; a separately labeled copy and its upstream license are available in the matching Internet Archive package. The source index and sitemap remain historical capture artifacts and may contain older publication pointers.

The separate supporting study-document collection is at https://archive.org/details/490d-supporting-study-documents-2026-09-30. Its files are not in this repository and are outside the canonical-corpus license. The existing `LICENSE.md` remains unchanged. The July Zenodo DOI and July GitHub release remain references to that earlier edition. The September capture is separately preserved at https://zenodo.org/records/23068909.
