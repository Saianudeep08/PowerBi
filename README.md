# Power BI Portfolio

This repository contains Power BI report files, supporting Excel datasets, archived source data, and mini-project material. The files are organized so reports, datasets, and project documentation are easy to find and reuse.

## Repository structure

```text
.
├── archives/
│   └── financial-sample-country-wise.zip
├── datasets/
│   ├── course-progress/
│   │   └── course-progress-data.xlsx
│   └── financial-samples/
│       ├── country-wise/
│       │   ├── Canada.xlsx
│       │   ├── France.xlsx
│       │   ├── Germany.xlsx
│       │   ├── Mexico.xlsx
│       │   └── United States of America.xlsx
│       └── financial-sample.xlsx
├── projects/
│   └── mini-project/
│       ├── mini-project-dataset.xlsx
│       └── power-bi-mini-project-guidelines.pdf
└── reports/
    ├── BI-1.pbix
    ├── BI-2.pbix
    ├── BI-3.pbix
    ├── BI-4.pbix
    ├── BI-5.pbix
    ├── Mini-pro.pbix
    ├── POWER-BI-4.pbix
    └── Tata_DV.pbix
```

## Folder guide

| Folder | Purpose |
| --- | --- |
| `reports/` | Power BI Desktop report files (`.pbix`). Open these files in Power BI Desktop to view, edit, or publish dashboards. |
| `datasets/financial-samples/` | Financial sample Excel workbooks used as source data for practice dashboards and analysis. |
| `datasets/financial-samples/country-wise/` | Country-specific financial sample workbooks for Canada, France, Germany, Mexico, and the United States of America. |
| `datasets/course-progress/` | Course progress dataset for learning-progress or completion-tracking analysis. |
| `projects/mini-project/` | Mini-project dataset and the related project guidelines PDF. |
| `archives/` | Original compressed source files retained for reference or re-extraction. |

## Reports included

- `BI-1.pbix` through `BI-5.pbix` — sequential Power BI practice/report files.
- `POWER-BI-4.pbix` — additional Power BI report file preserved with a normalized filename.
- `Mini-pro.pbix` — mini-project report file.
- `Tata_DV.pbix` — Tata data visualization report file.

## Getting started

1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Clone or download this repository.
3. Open any `.pbix` file from the `reports/` folder.
4. If Power BI prompts for missing data sources, update the source path to the matching workbook in the `datasets/` or `projects/mini-project/` folder.
5. Refresh the report to verify that visuals load correctly.

## Data source notes

- Keep source workbooks in the existing folder structure when possible. Moving datasets may require updating data source settings inside Power BI Desktop.
- The `archives/financial-sample-country-wise.zip` file is the original compressed version of the country-wise financial sample data.
- The extracted country-wise workbooks are already available under `datasets/financial-samples/country-wise/` for direct use.

## Recommended workflow

1. Add new `.pbix` files to `reports/`.
2. Add reusable Excel or CSV files to an appropriate subfolder under `datasets/`.
3. Add project-specific files to a dedicated folder under `projects/`.
4. Keep compressed originals or backups under `archives/` only when they are useful for reference.
5. Update this README whenever new reports, datasets, or projects are added.

## Maintenance checklist

- Use descriptive filenames without unnecessary timestamps when adding new files.
- Keep reports and datasets separated.
- Avoid committing temporary Power BI cache/export files.
- Verify report refresh paths after moving or renaming datasets.
