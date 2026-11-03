# MyReport – Finance Power BI project

Power BI Project (PBIP) for the 2024 finance report. The data comes from
`Simple_Finance_Dataset.xlsx` in the RPAImplementation SharePoint site
(Shared Documents > Power BI Dashboard > ROI Dashboard).

| Folder | Contents |
|---|---|
| `MyReport.SemanticModel/definition` | Semantic model as TMDL: tables, measures, relationships, Power Query |
| `MyReport.Report/definition` | Report pages and visuals (PBIR) |
| `MyReport.pbip` | Open this in Power BI Desktop |

## How changes get in

1. Create a branch, make the change in Power BI Desktop, and save.
2. Commit and open a pull request into `main`.
3. The code owner reviews and approves it. `main` is protected, so nothing
   merges without that approval.
4. After the merge, the *Version approved changes* workflow tags the commit
   as the next version (`v1.0.N`) and publishes a release listing the changes.

Every earlier version is available under **Releases**, and its files can be
checked out with `git checkout v1.0.N`.
