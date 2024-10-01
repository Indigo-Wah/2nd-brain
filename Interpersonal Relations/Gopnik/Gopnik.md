---
tags:
  - InterRelations/Gopnik
  - Person
---
# Gopnik

DocType:: Person
Relation:: Partner
Pronouns:: He, Him, His
Age:: 19
Birthday:: 01-01-1970

## Reports

### Incidents

```dataview
TABLE People, Dates, Actionable
WHERE DocType = "Report" AND ReportType = "Incident" AND TemplateBool != true
SORT file.name ASC
```

