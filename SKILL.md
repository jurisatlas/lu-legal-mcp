---
name: lu-legal-mcp-skill
description: Official Luxembourg (LU) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Luxembourg Legal Research & Multi-Tier Case Law Skill (`lu-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Luxembourg (LU)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `ECLI:LU:CASS:2024:10 or Legilux Mémorial A`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** 3 Justices de paix (Luxembourg, Esch-sur-Alzette, Diekirch), 2 Tribunaux d'arrondissement & Tribunal administratif
   - **Second Instance (Cantonal / Regional / Appellate):** Cour d'appel (Chambres civiles, commerciales, criminelles et sociales) & Cour administrative
   - **Supreme & Constitutional Instance:** Cour de cassation (Cour supérieure de justice) & Cour constitutionnelle du Grand-Duché de Luxembourg
   - **Primary Tiered Database:** JuCha / Justice.public.lu Base de Jurisprudence (Judiciaire, Administratif & Constitutionnel) (`https://justice.public.lu/fr/jurisprudence.html`)
