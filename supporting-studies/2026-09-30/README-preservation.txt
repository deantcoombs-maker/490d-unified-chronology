490d Research — Supporting Study Documents
Preservation snapshot: 2026-09-30 UTC

START HERE
Open START-HERE.html for a linked inventory. All 11 current collection documents are preserved as unchanged originals: 10 Markdown files and one PNG diagram, totaling 1,076,441 bytes. All match both the published SHA-256 values and published byte counts.

SCOPE
The exact requested page, https://research.490d.com/#study, was checked against https://research.490d.com/study-documents/ and its published catalog. Both list the same 11 documents. This is a bounded supporting-study collection, not a copy of all C-series research records or all archives mentioned by those documents. Original edition dates and draft status remain in force.

LAYOUT
originals/ — all unchanged downloadable study documents, once per unique SHA-256
source-metadata/ — unchanged catalog.json, source-guide.md, and published SHA256SUMS.txt; plus the observed collection-guide HTML DOM and exact study-section scope evidence
collection-inventory.json — provenance, filename mapping, source roles, editions, byte counts, hashes, verification, and deduplication
SHA256SUMS.txt — package-relative checksums for every other packaged file
RIGHTS-AND-EDITIONS.txt — no new license; source-level rights/edition findings
START-HERE.html — locally generated navigation with original files and live reading links

INTEGRITY
From this directory, run: sha256sum -c SHA256SUMS.txt
To verify the originals against the unchanged published checksum file, run from originals/: sha256sum -c ../source-metadata/SHA256SUMS.txt

SOURCE ROLES AND DEDUPLICATION
Nine originals use study-documents/files/. Two were downloaded unchanged from content-addressed existing-archive endpoints: the SP Noah–Shem register (GEAR_REGISTER.md) and the Mirror bilateral/8395 study. The source catalog records one and eight archive aliases respectively. Each unique byte sequence is stored once here; the aliases are retained as provenance in the inventory. There are 11 distinct document hashes and no repeated original payloads in this package.

The descriptive SP register catalog filename differs from its published download filename GEAR_REGISTER.md. The actual download filename is retained so the published checksums verify unchanged. Both names are mapped in collection-inventory.json.

HTML AND NAVIGATION
The collection guide is an observed browser DOM serialization, not a byte-identical HTTP response; it retains source-relative web links and may require the live site for styling/navigation. START-HERE.html is locally generated and works without that site for packaged originals. Full published report HTML renderings are linked but are not included: the unchanged Markdown and PNG originals are the authoritative preserved content. The diagram's accessible label transcription is retained in unchanged catalog.json.

UPLOAD LAYOUT
Standalone Internet Archive uploads flatten the package folders. The published checksum file is named source-SHA256SUMS.txt there, while SHA256SUMS.txt covers the flattened upload set. The ZIP retains the structured directory layout and its own relative checksums. The ZIP is intentionally an aggregate copy of the separately available files; it is not a distinct source edition.

RIGHTS
See RIGHTS-AND-EDITIONS.txt. No collection-wide reuse license is inferred or newly applied.
