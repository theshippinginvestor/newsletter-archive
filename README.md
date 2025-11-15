# Newsletter Archive - The Shipping Investor

Automatisches Archiv für alle Newsletter-Ausgaben.

## 📋 Struktur

```
/
├── index.html                  # Übersichtsseite (auto-generiert)
├── newsletters/                # Alle Newsletter-Ausgaben
│   ├── 2025-01-12.html
│   ├── 2025-01-19.html
│   └── ...
└── newsletters_metadata.json   # Metadaten (Headlines, Dates)
```

## 🔄 Automatische Updates

- Jeden Sonntag 09:00 CET wird automatisch ein neuer Newsletter hinzugefügt
- GitHub Actions Workflow pusht via `NEWSLETTER_ARCHIVE_PAT`
- Index wird automatisch mit allen Newslettern aktualisiert

## 🌐 GitHub Pages

**Live URL**: https://theshippinginvestor.github.io/newsletter-archive

## 🔧 System

- **Managed by**: GitHub Actions Workflow
- **Source Repository**: https://github.com/frankfuchs5000/the-shipping-investor
- **Generator**: `newsletter/github_archive_manager.py`
