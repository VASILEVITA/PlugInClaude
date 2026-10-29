# Pluginuri Claude Code instalate

Ce pluginuri am instalate în Claude Code și la ce folosește fiecare.

- **Instalate pe:** 29.10.2026
- **Scope:** `user` (sunt active în toate proiectele)
- **Sursă:** `anthropic-plugin-directory`
- **Total:** 29 de pluginuri

Skill-urile se apelează în Claude Code cu `/<plugin>:<skill>` (ex. `/superpowers:brainstorming`). Claude le poate folosi și singur, atunci când cererea se potrivește.

---

## Programare și dezvoltare

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **superpowers** | 6.4.2 | Bibliotecă de bază pentru lucrul disciplinat: brainstorming, planuri, TDD, debugging sistematic, code review, worktree-uri git | `brainstorming`, `writing-plans`, `systematic-debugging`, `test-driven-development` |
| **ai-skills** (`zizi-skills`) | 0.5.0 | Planificare, implementare test-first, review de cod și securitate, igienă git, predare de sesiune | `planning`, `code-quality`, `security-and-hardening`, `handoff` |
| **code-review-anthropics** | 1.0.1 | Review automat de pull request-uri cu mai mulți agenți specializați și scor de încredere | `/code-review:code-review` |
| **code-simplifier** | 1.0.0 | Agent care simplifică și curăță codul fără să-i schimbe comportamentul | agentul `code-simplifier` |
| **commit-commands** | 1.0.1 | Comenzi rapide pentru commit, push și pull request | `/commit-commands:commit`, `commit-push-pr`, `clean_gone` |
| **claude-security** | 0.11.0 | Scanare de vulnerabilități în propriul cod; fiecare problemă găsită e verificată de mai mulți agenți, apoi generează patch-uri | `/claude-security` |
| **claude-md-management** | 1.0.0 | Întreține fișierele `CLAUDE.md` (memoria proiectului): audit, actualizare cu ce s-a învățat | `revise-claude-md`, `claude-md-improver` |
| **microsoft-docs** | 0.3.1 | Acces la documentația oficială Microsoft (Azure, .NET, Windows) și exemple de cod | `microsoft-docs`, `microsoft-code-reference` |
| **desktop-commander** | 0.2.0 | Server MCP pentru comenzi în terminal, procese și operații pe fișiere (text, PDF, DOCX, Excel, imagini) | `terminal`, `computer-health-check`, `knowledge-base` |

## Date și finanțe

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **data** | 1.1.0 | SQL, explorare de seturi de date, statistici, grafice și dashboard-uri | `write-query`, `analyze`, `build-dashboard`, `create-viz` |
| **finance** | 1.3.0 | Contabilitate: note contabile, reconcilieri, situații financiare, analiză de abateri, închidere de lună, audit | `journal-entry`, `reconciliation`, `close-management` |

## Afaceri, vânzări și HR

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **small-business** | 1.35.1 | Fluxuri gata făcute pentru o firmă mică: facturi, cash-flow, salarii, taxe, stocuri, lead-uri, recenzii. Cere aprobare la orice pas care atinge bani sau clienți | `smb-onboard`, `invoice-chase`, `cash-flow-snapshot`, `monday-brief` |
| **sales** | 2.1.0 | Pregătire de apeluri, rezumate, cercetare de conturi, pipeline, forecast; lucrează cu CRM, email și calendar | `call-prep`, `pipeline-review`, `forecast`, `draft-outreach` |
| **human-resources** | 1.3.0 | Recrutare, onboarding, evaluări de performanță, analiză salarială, politici interne | `recruiting-pipeline`, `onboarding`, `performance-review` |
| **productivity** | 1.3.1 | Gestionare de sarcini, planificarea zilei, memorie despre contextul de lucru | `start`, `task-management`, `memory-management` |
| **enterprise-search** | 1.3.0 | Căutare într-un singur loc prin email, chat, documente și wiki-uri | `search`, `digest`, `knowledge-synthesis` |

## Juridic

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **legal** | 1.3.0 | Review de contracte, triaj NDA, conformitate, evaluare de risc, briefuri juridice | `review-contract`, `triage-nda`, `compliance-check` |
| **commercial-legal** | 1.0.2 | Contracte cu furnizori, NDA, abonamente SaaS comparate cu playbook-ul propriu; urmărește termenele de reînnoire | `nda-review`, `saas-msa-review`, `renewal-tracker` |
| **pdf-viewer** | 0.2.0 | Vizualizare, adnotare, completare de formulare și semnare de PDF-uri într-un viewer interactiv | `open`, `annotate`, `fill-form`, `sign` |

## Marketing, brand și conținut

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **marketing** | 1.2.0 | Conținut, campanii, emailuri, analiză de competiție, rapoarte de performanță | `campaign-plan`, `content-creation`, `email-sequence` |
| **brand-voice** | 1.1.0 | Strânge materialele de brand și le transformă în reguli aplicate la tot conținutul generat | `discover-brand`, `generate-guidelines`, `enforce-voice` |
| **social-media-skills** | 1.0.1 | 106 skill-uri pentru social media: strategie, texte, video, design, creștere pe platforme, analiză | `caption-writer`, `content-calendar`, `tiktok-script`, `linkedin-post-writer` |
| **design** | 1.2.0 | Critică de design, design system, texte UX, audit de accesibilitate, predare către dezvoltatori | `design-critique`, `ux-copy`, `accessibility-review` |
| **humanizer-blader** | 3.1.0 | Rescrie textul care sună a AI ca să sune natural, fără să-i schimbe sensul | `humanizer` |
| **image-generation** | 1.0.0 | Ghid de prompt-uri pentru modele text-to-image (Imagen, GPT Image, Flux, Midjourney etc.) | `image-generation` |
| **watch-video** | 1.0.0 | Claude „se uită” la un video (fișier local sau URL): extrage cadre cheie, transcrie audio, face un raport | `watch-video` |

## SEO

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **seo-aeo-geo-ultimate** | 3.3.0 | Router SEO / AEO / GEO / AI-search cu 27 de skill-uri specializate; rulează ce se aplică și dă un singur rezultat | `seo`, `seo-audit`, `seo-technical`, `seo-schema` |
| **claude-seo-and-geo-site-audit** | 1.0.0 | Audit de site (SEO, accesibilitate, GEO, pregătire pentru căutarea cu AI), cu raport PDF, notă și priorități | `site-audit` |

## Canale de mesagerie

| Plugin | Versiune | La ce folosește | Exemple de skill-uri / comenzi |
|---|---|---|---|
| **telegram** | 0.0.7 | Legătură între Telegram și Claude Code, cu control de acces | `/telegram:configure`, `/telegram:access` |
| **instagram** | 0.2.0 | Citire și răspuns la comentarii și mesaje directe pe Instagram, prin API-ul oficial | `/instagram:configure`, `/instagram:access` |

---

## Ce trebuie configurat

Skill-urile merg imediat după instalare, dar unele pluginuri folosesc servere MCP care au nevoie de autentificare sau configurare:

- **telegram** și **instagram** nu s-au conectat. Trebuie configurate cu `/telegram:configure` și `/instagram:configure`.
- **Conectori care așteaptă autorizare** (Notion, Slack, Figma, Canva, Salesforce, Atlassian, Microsoft 365 etc.) se autorizează cu `/mcp` într-o sesiune interactivă.
- Câțiva conectori nu se pot conecta deloc din partea serverului: BigQuery, Asana, Box, HubSpot, Xero, Zoom, Definely, TopCounsel, Definite.

## Note

- La început erau instalate două pluginuri humanizer cu același nume intern. Am păstrat `humanizer-blader` (originalul) și l-am dezinstalat pe `humanizer-adelaidasofia`.
- Lista completă și actualizată e în `~/.claude/plugins/installed_plugins.json`.
