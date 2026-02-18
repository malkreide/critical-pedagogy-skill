# Critical Pedagogy Skill

🇬🇧 **English** | [🇩🇪 Deutsch](README_DE.md)

**Critical-pedagogical analysis of educational texts, curricula, school structures, and communication**

A [Claude AI Skill](https://docs.claude.com) for the systematic examination of educational documents for hidden power dynamics, exclusion mechanisms, and normative assumptions — based on Critical Theory and Critical Pedagogy.

## Overview

No educational text is neutral. Every document conveys — consciously or unconsciously — assumptions about who is "normal," what "good learning" means, and whose knowledge counts. This skill makes these assumptions visible and translates critical theory into a practical tool for education professionals.

### Theoretical Foundations

| Tradition | Core Concept |
|---|---|
| **Frankfurt School** (Horkheimer/Adorno) | Instrumental reason, ideology critique |
| **Habermas** | Colonization of the lifeworld, communicative reason |
| **Honneth** | Recognition and disrespect |
| **Freire** | Banking concept, conscientização, dialogical pedagogy |

### Context Calibration

The skill is calibrated for the **Swiss education system** (particularly the City of Zurich), referencing the Lehrplan 21 (Curriculum 21), the Volksschulgesetz (Public School Act), the UN Convention on the Rights of the Child, and the specific framework conditions of Swiss public schools.

**Note for international users:** While calibrated for Switzerland, the analytical methodology is universally applicable. When analyzing texts from other educational systems, replace the Swiss legal references with your local legal frameworks (e.g., IDEA/Title IX in the US, Equality Act in the UK). The five analytical steps and theoretical framework remain the same.

## The 5 Analysis Steps

1. **Contextualization** — "Who speaks, to whom, for what purpose?"
2. **Normativity Analysis** — "What is set as 'normal'?"
3. **Power Analysis** — "Who benefits, who loses?"
4. **Perspective Shift** — "Who is missing? Who is unheard?"
5. **Constructive Transformation** — "What could be different?"

Each finding is marked with a **data quality indicator:**
- 🔵 **Evidenced** — verifiable facts
- ⚪ **Estimate** — plausibility assumptions

## Use Cases

- Examine curricula and teaching materials for bias and inclusion
- Analyze school communication (parent letters, mission statements, policies) for implicit assumptions
- Question school structures and processes for systemic disadvantage
- Conduct diversity audits of educational materials
- Analyze selection processes
- Develop inclusive school cultures

## Quick Modes

| Mode | Scope | Best for |
|---|---|---|
| **Quick Analysis** | ~500 words | Parent letter, flyer |
| **Standard Analysis** | ~1000–1500 words | School program, policy |
| **Deep Analysis** | Full depth | Curriculum, concept paper |

## Installation

### Claude.ai (Projects)

1. Create a new project or open an existing one
2. Go to **Project Knowledge**
3. Upload the `SKILL.md` (German) or `SKILL_EN.md` (English) file
4. The skill is immediately ready to use

### Claude Desktop (Skills)

1. Copy the skill file into your skills directory:
   - **macOS:** `~/Library/Application Support/Claude/skills/critical-pedagogy/SKILL.md`
   - **Windows:** `%APPDATA%\Claude\skills\critical-pedagogy\SKILL.md`
2. Restart Claude Desktop

### Other Platforms

Copy the content of the skill file into the system prompt or project instructions of your preferred Claude integration.

## Language Versions

| File | Language | Description |
|---|---|---|
| `SKILL.md` | 🇩🇪 German | Original version, calibrated for Swiss context |
| `SKILL_EN.md` | 🇬🇧 English | English translation for international use |

Both versions are functionally equivalent. The German version uses Swiss German spelling conventions (no ß, Guillemets « » instead of „ ") and contains Swiss-specific legal references. The English version includes a note on adapting the legal framework to other jurisdictions.

## Example

**Input:**
> "Dear Parents, please support your child in daily vocabulary practice. It is important that a quiet workspace is available at home."

**Analysis (excerpt):**

- 🟠 *Implicit norm:* "Parents" assumes at least one adult is available and competent enough to help with practice. Blanked out: families where no parent speaks the dominant language. ⚪
- 🟠 *Implicit norm:* "Quiet workspace" assumes living conditions that allow for a dedicated room. Blanked out: cramped living conditions. ⚪

**Recommendation (🟢 Immediately actionable):**
- *Before:* "Please support your child in daily vocabulary practice."
- *After:* "It helps your child to practice vocabulary regularly — for example while shopping, on the way to school, or with a learning app. If you have questions or would like support, please don't hesitate to contact us."

## Related Skills

- [musk-algorithm-skill](https://github.com/malkreide/musk-algorithm-skill) — Process optimization using the 5-step algorithm
- [socratic-method-skill](https://github.com/malkreide/socratic-method-skill) — Socratic method as a teaching and learning tool

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Author

**Hayal Oezkan**
- GitHub: [@malkreide](https://github.com/malkreide)
- LinkedIn: [hayaloezkan](https://www.linkedin.com/in/hayaloezkan/)

---

<div align="center">

**Made with ❤️ in Zürich**

[LinkedIn](https://www.linkedin.com/in/hayaloezkan/) • [Contributing](CONTRIBUTING.md)

</div>
