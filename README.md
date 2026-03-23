# HAI-ATTR
## Human-AI Attribution Standard — v0.1

**Originating author: Robert McQueen, Harrisville, New York**
**Proposed: March 23, 2026**
**License: [CC BY 4.0](./LICENSE.txt)**

---

## What is HAI-ATTR?

HAI-ATTR is a lightweight attribution standard for documents produced through human-AI collaboration. It answers a question that APA, MLA, Chicago, and other citation standards do not: *who did the thinking?*

Existing citation standards handle source attribution — where did the information come from. HAI-ATTR handles process attribution — who originated the ideas, who synthesized the research, who generated the prose, and who verified the result. These are different questions, and the difference matters for academic integrity, professional accountability, and honest public communication.

---

## The Problem HAI-ATTR Solves

A document where a human typed a one-sentence prompt and accepted unedited AI output is fundamentally different from a document where a human drove hours of analytical development, originated all core insights, and used AI as a research and prose generation tool under continuous editorial direction. Existing standards treat both identically — or ignore the AI contribution entirely.

HAI-ATTR provides a structured, minimal, visually unobtrusive way to make that distinction visible in the document itself.

---

## The Four Tags

| Tag | Meaning |
|-----|---------|
| `[H]` | **Human-originated** — the idea, frame, or conclusion came from the human author |
| `[AI]` | **AI-generated** — produced by the AI without specific human direction beyond general task framing |
| `[H->AI]` | **Human-directed AI synthesis** — human identified the direction; AI researched, structured, or articulated |
| `[AI->H]` | **AI-generated, human-verified** — AI produced the content; human verified accuracy and approved inclusion |

Tags appear at the end of the passage they describe, rendered in a visually subordinate style. When used with a numbered reference system, tags take the form `[TYPE]^N` where N points to a numbered entry in the document's colophon.

---

## Visual Convention

- **Tag brackets:** approximately two-thirds the body font size
- **Superscript number:** standard footnote number size — slightly larger than the tag, acting as visual anchor
- **Color:** muted, distinct from body text
- **Minimum superscript size:** 6pt — legible at standard zoom without magnification

The number pulls the reader's eye first. The bracket provides context on deliberate inspection. A reader who trusts the document ignores both. A reader who wants to verify follows the number to the colophon.

---

## The Colophon

Documents using HAI-ATTR include a colophon — a dedicated attribution record containing:

- Package identification (title, date, author, AI platform)
- Session context (brief description of working method)
- Named human contributions
- Named AI contributions
- Full numbered tag reference entries

The colophon borrows from the medieval manuscript tradition in which scribes recorded the circumstances of a document's production as part of the work itself.

---

## Reference List Placement

In documents using a standard reference list (APA, MLA, Chicago, or equivalent), the HAI-ATTR citation appears as the **final entry**, separated from substantive source citations by a horizontal rule or blank line. HAI-ATTR describes how the document was made, not where its information came from. The colophon follows the reference list entirely. This convention applies regardless of citation format used in the body of the document.

**APA:**
```
McQueen, R. (2026, March 23). HAI-ATTR v0.1: Human-AI attribution
   standard. Zenodo. https://doi.org/10.5281/zenodo.19177209
```

**MLA:**
```
McQueen, Robert. "HAI-ATTR v0.1: Human-AI Attribution Standard."
   23 Mar. 2026, Zenodo, https://doi.org/10.5281/zenodo.19177209

---

## Document-Level HAI-ATTR Block

Every document using the standard includes this block in the footer or colophon:

```
HAI-ATTR v0.1 | Human author: [name] | AI platform: [platform, version, provider]
Session date: [date] | Working method: [one-line description]
Human vouches for content accuracy: [Yes/No] | Estimated ratio: [approximate]
```

---

## What HAI-ATTR Does Not Do

- Replace source citation standards — APA, MLA, Chicago remain the tools for content attribution
- Reduce human accountability — the human author vouches for all content regardless of tag type
- Claim completeness — v0.1 is a working draft; edge cases and extensions are expected

---

## Known Open Problems (v0.2 Scope)

- Recommended citation string format for citation management tools (Zotero, EndNote)
- Digital image and visual media extension — proposed: QR code embedded in image composition, visually present and noticeable if removed or obscured
- Handling of multi-session documents where sessions had different human-AI ratios
- Additional tag types for genuinely indistinguishable co-creation

---

## Version History

| Version | Date | Notes |
|---------|------|-------|
| v0.1 | March 23, 2026 | Initial draft. First applied to a constituent letter package submitted to Senator Charles Schumer (D-NY). |

---

## Contributing

Proposed revisions, edge case reports, and adoption notices are welcome via GitHub Issues or Pull Request. Reference the section you are addressing and describe the problem the change solves.

---

## License

CC BY 4.0 — see [LICENSE.txt](./LICENSE.txt)

*HAI-ATTR — because "who did the thinking" is a question worth answering.*
