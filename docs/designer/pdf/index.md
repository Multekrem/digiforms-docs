# PDF Documents

Digiforms Designer can be used to create XML-driven templates for automated PDF generation.

PDF templates define the layout, formatting and structure of documents rendered from XML data.

---

## How PDF generation works

PDF output in Digiforms is based on:

- XML (data source)
- XPath (data selection)
- XSLT (transformations)
- XSL-FO (layout definition)

The Designer generates XSL-FO markup in the background.

The resulting templates can be rendered using any XSL-FO compliant PDF renderer.

---

## Typical use cases

PDF templates are commonly used for:

- Reports
- Official documents
- Letters and notices
- Structured document automation
- Output generated from form submissions

---

## Layout and formatting

PDF layout is defined using XSL-FO concepts such as:

- Page masters
- Regions
- Blocks and inline elements
- Tables
- Alignment and spacing

See:

- [Layout](layout/index.md)
- [Alignment](alignment/index.md)
- [Tables](tables/index.md)
- [XSL-FO Reference](xsl-fo/index.md)

---

## Fonts and rendering

Fonts must be properly configured in the PDF renderer environment.

See:

- [Fonts in PDF](fonts/index.md)

---

## Data binding

PDF templates bind XML data to layout elements using XPath expressions.

See:

- [Data Model](../data-and-structure/data-model/index.md)
- [Datasources](datasources/index.md)

---

## Preview and testing

Digiforms Designer includes PDF preview functionality to test templates during development.

For server-side rendering and deployment, see:

- [Digiforms Server](../../server/index.md)
