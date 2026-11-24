# Global SEO Agency Technical Quality, Core Web Vitals & Transparency Benchmark (November 2026)

[![Live Index](https://img.shields.io/badge/Live%20Index-goodseocompanies.com-c8361c)](https://goodseocompanies.com)
[![Methodology](https://img.shields.io/badge/Methodology-v1.0-111111)](https://goodseocompanies.com/methodology/)
[![Harvard Dataverse DOI](https://img.shields.io/badge/Harvard%20Dataverse-10.7910%2FDVN%2FNF4JBZ-blue)](https://doi.org/10.7910/DVN/NF4JBZ)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Open empirical dataset of automated technical SEO audits, Google PageSpeed Insights (Core Web Vitals) measurements, and structured website transparency observations across **1,693 SEO agency websites** collected in November 2026 as part of the independent, evidence-based [Good SEO Companies](https://goodseocompanies.com) index.

## Key Empirical Findings (November 2026)
- **1,693** SEO agency websites audited across major cities in the US, UK, Canada, Australia, and Ireland
- **1,390** agencies with Core Web Vitals (LCP) measurements — only **31.8%** (`442 / 1,390`) pass Google's `LCP <= 2500 ms` threshold
- **96.2%** (`1,629 / 1,693`) serve HTTPS on their homepage
- Only **17.8%** (`301 / 1,693`) publish transparent pricing on their website

## Public Methodology & Live Data
Every agency in the [Good SEO Companies](https://goodseocompanies.com) index is evaluated under the same public 7-factor rubric ([Methodology v1.0](https://goodseocompanies.com/methodology/)) with zero paid placements:
1. Proof of results (25%) — own-site Google rankings + measurable case studies
2. Client reviews (20%) — verified rating & volume curve
3. Own-site technical quality (15%) — Core Web Vitals (LCP, INP, CLS), HTTPS, indexability, Organization schema, XML sitemap
4. Transparency (15%) — published pricing, named team, physical address, contact page
5. Demonstrated expertise (10%) — bylined articles, talks, research, or awards
6. Longevity (10%) — founding year & domain age
7. Specialisation (5%) — focused vs. generalist positioning

Machine-readable index overview for LLMs and agents: [`https://goodseocompanies.com/llms.txt`](https://goodseocompanies.com/llms.txt)

## Dataset Schema (`seo-agency-technical-transparency-benchmark-2026-11.csv`)
| Column | Description |
|---|---|
| `domain` | Public agency domain |
| `agency_name` | Extracted agency name |
| `offers_seo` | Whether SEO services are offered (`true`/`false`) |
| `cities` | Pipe-delimited cities where the agency was discovered |
| `https` | Homepage served over valid HTTPS (`true`/`false`) |
| `unreachable` | Whether homepage failed to load during audit |
| `psi_source` | PageSpeed Insights data source (`crux` or `lab`) |
| `lcp_ms` | Largest Contentful Paint in milliseconds |
| `inp_ms` | Interaction to Next Paint in milliseconds |
| `cls` | Cumulative Layout Shift |
| `lighthouse_perf` | Lighthouse performance score (`0`–`1`) |
| `pricing_published` | Transparent pricing published (`true`/`false`) |
| `team_named` | Named leadership/team listed (`true`/`false`) |
| `address_published` | Physical office address published (`true`/`false`) |
| `bylined_content` | Articles signed by named practitioners (`true`/`false`) |
| `case_study_count` | Number of extracted case studies |
| `audited_at` | UTC ISO-8601 audit timestamp |

## Academic Citation
> Good SEO Companies (2026). *Global SEO Agency Technical Quality, Core Web Vitals & Transparency Benchmark (November 2026)*. Harvard Dataverse. https://doi.org/10.7910/DVN/NF4JBZ · Live index: https://goodseocompanies.com

## License
Creative Commons Attribution 4.0 International (CC BY 4.0). You may share and adapt the dataset with attribution linking to [https://goodseocompanies.com](https://goodseocompanies.com).
