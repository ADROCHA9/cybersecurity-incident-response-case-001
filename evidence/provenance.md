# Evidence provenance and integrity

The original research archive includes notes, historical filesystem records, indicators, a behavior matrix, defensive scripts and YARA rules. The malicious extension archive is retained separately and is not distributed.

## Retrospective integrity review — 2026-11-19

- Extension archive SHA-256: `27CB071BE2B985C112A4F628D592325396E6F37DB87163DC71177EFE3B3EEC3C`.
- Archive hash matches the historical inventory.
- 47 of 47 file entries match historical path, byte size and SHA-256. The inventory contains another 17 directory entries, excluded from the file count.
- Method: read ZIP entries as bytes without extracting or executing them; compare with analysis/hashes.csv in the historical research archive.

This demonstrates consistency with the supplied inventory, not independent proof of acquisition time or a formal chain of custody. The MSI hash is historical; the MSI was not available for rehashing.

## Publication copies

The filesystem extract replaces the local user prefix with %LOCALAPPDATA%. The IoC inventory masks the IP and omits the download endpoint. Defensive code is reproduced as documentary text, not execution output. Financial evidence is described separately. No final remediation transcript is available.
