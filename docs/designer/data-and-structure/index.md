# Data and Structure

All solutions built in Digiforms Designer are based on a shared XML-driven data model.

Whether the output is a PDF document or a web application, the same foundational concepts apply.

This section describes how data is structured, accessed and reused across templates.

---

## The XML Data Model

At the core of every Digiforms template is an XML document.

The XML defines:

- Data structure
- Hierarchy
- Element relationships
- Repeating nodes

Both PDF layout and web controls bind to this structure using XPath expressions.

See:

- [Data Model](data-model/index.md)
- [XML Structure](data-model/xml/index.md)
- [XPath](data-model/xpath/index.md)
- [Revisions](data-model/revisions/index.md)

---

## Datasources

Datasources define where data originates and how it is connected to the XML model.

In web applications, datasources may retrieve or persist data.
In PDF generation, datasources typically provide structured input for rendering.

See:

- [Datasources Overview](datasources/index.md)

---

## Components

Components allow reuse of structured content and behavior across templates.

They help maintain consistency and reduce duplication in:

- Layout elements
- Repeating structures
- Shared logic

See:

- [Components](components/index.md)

---

## Shared foundation

Data and structure concepts are used by:

- [PDF Documents](../pdf/index.md)
- [Web Applications](../web/index.md)

Understanding the XML model and binding mechanisms is essential when building larger or more complex solutions.
