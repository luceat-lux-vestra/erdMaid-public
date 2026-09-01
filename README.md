# erdMaid

**Export database tables as Mermaid ER diagrams from JetBrains IDEs.**

erdMaid is a JetBrains IDE plugin for turning table metadata from the Database tool window into Mermaid `erDiagram` syntax. It is intended for developers who want a fast way to move real schema structure into Markdown, documentation, and architecture notes without rewriting table definitions by hand.

## Highlights

- Export every table in a schema's `Tables` node or only selected tables
- Preserve the column order reported by database metadata
- Include primary keys and foreign-key relationships
- Include column types and comments
- Render size, precision, and scale in a Mermaid-safe representation
- Copy generated Mermaid directly to the clipboard
- Work inside IntelliJ IDEA Ultimate, DataGrip, and compatible JetBrains IDEs with database tooling

## Typical workflow

1. Open the **Database** tool window.
2. Expand a schema and its `Tables` node.
3. Select the `Tables` node or individual tables.
4. Choose **Export as Mermaid ERD (erdMaid)**.
5. Paste the generated diagram into Markdown or another Mermaid-enabled document.

## Output

The exporter generates Mermaid `erDiagram` definitions from the metadata already available to the IDE. Table comments are emitted as Mermaid comments, column metadata is normalized for Mermaid parsing, and relationships are derived from foreign-key information.

## Scope

The project currently focuses on database tables and Mermaid ER diagrams. View export and alternative diagram formats are intentionally outside the current scope.

## Status

erdMaid is under active development. Marketplace publication and repository consolidation are still in progress.
