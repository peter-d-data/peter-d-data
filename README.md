<div align="center">
  <!-- Replace the link below with the actual URL/path to your exported Canva banner -->
  <img src="banner.png" alt="peter-d-data: Software Asset Management & BI Expert" width="100%" />
</div>

<br>

# Peter D

Software asset management — licensing, compliance and entitlement analysis across enterprise estates. Licensing depth in IBM, Red Hat, Microsoft, Adobe and Oracle: programme rules, contract vehicles, and the conditions that decide which apply.

Currently rebuilding how I do that work. Less spreadsheet, more model.

## 🏗️ What I'm building

The through-line is reconciliation — discovery data on one side, entitlements on the other, and a defensible position in between. Most of that is a data engineering problem wearing a procurement hat.

Working through it roughly in this order, deliberately not skipping ahead:

1. **Target model sketch** — fact grain and dimensions declared before any transformation
2. **Power Query (M)** — normalisation, custom functions, query folding
3. **SQL** — reading and auditing it more than authoring it; window functions, CTEs, anti-joins
4. **dbt** — transformations as tested, version-controlled models
5. **Dimensional modelling** — cardinality, filter direction, slowly changing dimensions
6. **DAX and Power BI** — filter context, and reporting that leads to a decision

## ⚙️ Stack

`Power Query (M)` · `SQL` · `dbt` · `Power BI / DAX` · `DuckDB` · `PostgreSQL` · `Podman` · `Arch / Hyprland`

Excel to an advanced standard, which is precisely why I'm moving the heavy lifting out of it.

## 🔒 On the repositories

Most are private and will stay that way. None of them contain employer data, client data, or anything from a live extract — where I need realistic input I generate synthetic data matching the structure, defects and all: inconsistent vendor naming, orphaned records, date gaps, duplicate hosts.

Public repos are method, not material.
