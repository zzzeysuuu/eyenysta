# EyeNysta

Senior design project website.

## Yeni belge ekleme (her teslimde)

1. Repoda `reports` klasörüne girin → **Add file → Upload files** → PDF'i sürükleyin → **Commit changes**.
   Dosya adında Türkçe karakter ve boşluk kullanmayın, örn. `project-proposal.pdf`.
2. Ana dizindeki `reports.json` dosyasını açın → kalem simgesi (Edit) → belgeyi listeye ekleyin → **Commit changes**.

```json
[
  { "deliverable": "Project Proposal", "file": "reports/project-proposal.pdf", "date": "2026-10-30" }
]
```

İkinci belgede satırların arasına virgül koyun:

```json
[
  { "deliverable": "Project Proposal", "file": "reports/project-proposal.pdf", "date": "2026-10-30" },
  { "deliverable": "Project Specifications Report", "file": "reports/specifications.pdf", "date": "2026-11-20" }
]
```

`deliverable` alanı şu isimlerden biriyle **birebir aynı** yazılmalı:
Project Proposal · Project Specifications Report · Backlog 1 · Project Analysis Report · Backlog 2 · High-Level Design Report · Backlog 3

İsteğe bağlı olarak `"note": "Revised version"` eklenebilir. Site 1–2 dakika içinde güncellenir.
