# frontend-prime-skills

AI agent'lar için frontend geliştirme skill'i. Jenerik "AI slop" çıktılarına son.

---

## 🇹🇷 Türkçe

### Kurulum

```bash
npx skills add EsraMulkpinar/frontend-prime-skills
```

### Agent'a Göre Kurulum

```bash
npx skills add EsraMulkpinar/frontend-prime-skills -a claude-code   # Claude Code
npx skills add EsraMulkpinar/frontend-prime-skills -a cursor         # Cursor
npx skills add EsraMulkpinar/frontend-prime-skills -a vscode         # VS Code / Copilot
npx skills add EsraMulkpinar/frontend-prime-skills -a codex          # Codex
npx skills add EsraMulkpinar/frontend-prime-skills -a windsurf       # Windsurf
npx skills add EsraMulkpinar/frontend-prime-skills -a '*'            # Hepsine birden
```

### Claude.ai'da Kullanım

**Proje bazlı (önerilen):** claude.ai → Projects → Project Knowledge → `SKILL.md` sürükle-bırak. O projedeki her sohbette aktif olur.

**Tek sohbet:** 📎 ataç ikonuna tıkla → `SKILL.md` yükle.

### Ne yapıyor?

AI agent'lar hep aynı çıktıyı veriyor: mor gradient, Inter font, simetrik card grid, SEO yok. Bu skill şunları düzeltiyor:

- Önce tasarım kararı al, sonra kodla
- AI slop blacklist — jenerik görünümden kaçın
- Kişilikli font ve renk sistemi kur
- Dark mode'u doğru yap (3 katmanlı token mimarisi)
- SEO'yu unutma (meta, OG, JSON-LD, sitemap)
- Erişilebilirlik, performans, güvenlik hatırlatmaları

### Neden sadece ~100 satır?

Agent'lar Zod, Error Boundary, CSP gibi şeyleri zaten biliyor. Tekrar öğretmek token israfı. Bu skill sadece agent'ların varsayılan olarak yanlış yaptığı veya unuttuğu şeyleri içeriyor.

---

## 🇬🇧 English

### Install

```bash
npx skills add EsraMulkpinar/frontend-prime-skills
```

### Per Agent

```bash
npx skills add EsraMulkpinar/frontend-prime-skills -a claude-code     # Claude Code
npx skills add EsraMulkpinar/frontend-prime-skills -a cursor           # Cursor
npx skills add EsraMulkpinar/frontend-prime-skills -a vscode           # VS Code / Copilot
npx skills add EsraMulkpinar/frontend-prime-skills -a codex            # Codex
npx skills add EsraMulkpinar/frontend-prime-skills -a windsurf         # Windsurf
npx skills add EsraMulkpinar/frontend-prime-skills -a '*'              # All agents
```

### Using on Claude.ai

**Project-based (recommended):** claude.ai → Projects → Project Knowledge → drag & drop `SKILL.md`. Active in every chat within that project.

**Single chat:** Click 📎 → upload `SKILL.md`.

### What it does

AI agents keep producing the same generic output: purple gradients, Inter font, symmetrical card grids, no SEO. This skill fixes that:

- Design decisions before code
- AI slop blacklist — what never to do
- Distinctive fonts and color systems
- Dark mode done right (3-layer token architecture)
- SEO by default (meta, OG, JSON-LD, sitemap)
- Accessibility, performance, security reminders

### Why only ~100 lines?

Agents already know Zod, Error Boundaries, CSP headers. Re-teaching wastes tokens. This skill only contains what agents get wrong by default or tend to forget.
