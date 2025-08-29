# Reports

Report definitions and templates in mrp_flattened_bom_xlsx.

```mermaid
classDiagram
    class FlattenedBomXlsx
    AbstractModel <|-- FlattenedBomXlsx
```

## Available Reports

### PDF/Document Reports
- **Export Flattened BOM Structure to Excel** (PDF/Print)


## Report Files

- **flattened_bom_xlsx.py** (Python logic)
- **flattened_bom_xlsx.xml** (XML template/definition)
- **__init__.py** (Python logic)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
