# Zotero Hebrew CSL

CSL (Citation Style Language) XML implementations of Hebrew citation styles for use in Zotero.

This repository translates official Israeli and Hebrew-language citation guidelines into structured CSL XML files compatible with Zotero and other CSL-based reference managers.

**Status: Work in Progress**
All styles in this repository are currently under active development and may not fully conform to official journal guidelines.

---

## Purpose

Many Hebrew journals publish citation rules in prose (PDF/Word). In order to use these styles in Zotero, those rules must be formally encoded into CSL XML.

This repository aims to:

- Implement Hebrew and Israeli citation styles in CSL
- Encode right-to-left (RTL) and Hebrew-specific formatting behavior
- Provide transparent style definitions for review and improvement
- Iteratively refine accuracy against official guidelines

At this stage, styles may contain omissions, simplifications, or unresolved edge cases.

---

## Styles

### Drafts

These style files are functional drafts under active development. They may not fully conform to official journal guidelines and should be tested before use in formal submissions.

- [**Tarbiz**](https://jstudies.huji.ac.il/book/%D7%B4%D7%AA%D7%A8%D7%91%D7%99%D7%A5%D7%B4) (`tarbiz.csl`)
- [**Zion**](https://www.historical.org.il/Magazine/%D7%9B%D7%AA%D7%91-%D7%A2%D7%AA-%D7%A6%D7%99%D7%95%D7%9F/) (`zion.csl`)

---

## Installing a Style in Zotero

1. Download the `.csl` file.
2. Open Zotero.
3. Go to:
    ```txt
    Zotero → Settings → Cite → Styles
    ```
4. Click **+** (Add Style).
5. Select the downloaded file.

---

## Scope

This repository currently focuses on:

- Structural correctness under the CSL specification
- Progressive alignment with official Hebrew journal requirements
- Identification and resolution of edge cases in Hebrew citations

It does not yet guarantee:

- Full compliance with every published style rule
- Exhaustive coverage of all source types
- Institutional approval

---

## Contributing

Contributions are welcome. Since this is a work in progress, feedback and corrections are especially valuable.

Please:

- Validate styles before submitting changes
- Reference the official guideline being implemented
- Document any interpretive decisions

---

## Resources

### [CSL: Citation Style Language](https://docs.citationstyles.org)

- [CSL Specification](https://docs.citationstyles.org/en/stable/specification.html)
- [CSL Primer](https://docs.citationstyles.org/en/stable/primer.html)
- [CSL GitHub Repository](https://github.com/citation-style-language)
- [CSL Styles Repository](https://github.com/citation-style-language/styles)
- [CSL Validator](https://validator.citationstyles.org/)
- [CSL Visual Editor](https://editor.citationstyles.org/)

### [Zotero](https://www.zotero.org/)

- [Citation Styles](https://www.zotero.org/support/styles)
- [Zotero CSL Customization](https://www.zotero.org/support/csl_customization)
