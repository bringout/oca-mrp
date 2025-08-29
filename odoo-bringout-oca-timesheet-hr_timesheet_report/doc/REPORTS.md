# Reports

Report definitions and templates in hr_timesheet_report.

```mermaid
classDiagram
    class HrTimesheetReport
    TransientModel <|-- HrTimesheetReport
    class HrTimesheetReportAbstractField
    AbstractModel <|-- HrTimesheetReportAbstractField
    class HrTimesheetReportGroupByField
    TransientModel <|-- HrTimesheetReportGroupByField
    class HrTimesheetReportEntryField
    TransientModel <|-- HrTimesheetReportEntryField
    class HrTimesheetReportGroup
    TransientModel <|-- HrTimesheetReportGroup
    class HrTimesheetReportEntry
    TransientModel <|-- HrTimesheetReportEntry
    class Report
    AbstractModel <|-- Report
```

## Available Reports

### PDF/Document Reports
- **Timesheet Report** (PDF/Print)
- **Timesheet Report** (PDF/Print)
- **Timesheet Report** (PDF/Print)


## Report Files

- **hr_timesheet_report.py** (Python logic)
- **hr_timesheet_report.xml** (XML template/definition)
- **__init__.py** (Python logic)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
