# Digiforms Designer

Digiforms Designer is a graphical development tool for building XML-driven document templates and web-based applications.

Designer defines:

- Data structure
- Layout and presentation
- User interaction
- Reusable components

---

## What you can build

Digiforms Designer supports two primary output types:

- [PDF Documents](pdf/index.md)
- [Web Applications](web/index.md)

Both are built on the same XML-driven architecture.

Shared foundational concepts:

- [Data and Structure](data-and-structure/index.md)

---

## XML-driven architecture

Templates created in Digiforms Designer are based on:

- XML (data structure)
- XPath (data selection)
- XSLT (transformations)
- XSL-FO (layout and formatting)

These technologies are described in more detail under:

- [Data Model](data-and-structure/data-model/index.md)
- [Components](data-and-structure/components/index.md)
- [Datasources](data-and-structure/datasources/index.md)

The Designer generates XSL-FO with Digiforms-specific extensions to support interactive forms and web functionality.

---

## PDF generation

PDF templates can be used to generate documents through any XSL-FO compliant renderer.

See:

- [PDF Overview](pdf/index.md)
- [Layout and Formatting](pdf/layout/index.md)
- [Fonts in PDF](pdf/fonts/index.md)

---

## Web applications

When deployed with Digiforms Server, templates can be used to create browser-based applications.

See:

- [Web Overview](web/index.md)
- [Page Templates](web/page-templates/index.md)
- [Form Controls](web/form-controls/index.md)
- [Validation](web/validation/index.md)

Server runtime and integrations are documented under:

- [Digiforms Server](../server/index.md)

---

## System requirements

Digiforms Designer requires:

- Windows operating system
- Java (for PDF preview functionality)
- An XSL-FO compliant PDF renderer (e.g. Apache FOP)
- PDF reader software for viewing generated output
