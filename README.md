# credit-monitor data mirror

Machine-readable mirror of public credit-market series, refreshed daily.

- `series.csv` — long format: `date,series_id,value`
- `derived.csv` — computed metrics: `date,metric_id,value`
- `meta.json` — series names, units, cadence, last observation date

Every series here is republished from a public statistical release
(FRED / ICE BofA, ADB, national central banks and regulators). Consult
the original publishers for authoritative values, licensing and terms —
in particular, ICE BofA index data carries redistribution restrictions
and is included only where the upstream licence permits.

Observable market data only. Nothing here is a return figure, a
recommendation, or investment advice; standard disclaimers apply.

Provided as-is, with no warranty of accuracy or timeliness. This
repository is generated automatically; do not open pull requests
against it.
