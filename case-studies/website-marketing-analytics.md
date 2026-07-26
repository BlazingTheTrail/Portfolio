# Website Traffic & Marketing Campaign Analytics

> Confidential client engagement. This case study intentionally omits the client’s identity, website, source records, credentials, production queries, and commercially sensitive metrics.

## Business Context

A Canadian organization relied on its website as an important acquisition and communication channel. Existing GA4 reporting supported basic monitoring, but stakeholders needed a more accessible view of website traffic and campaign performance.

The engagement focused on making the data easier to query, validate, interpret, and present through stakeholder-oriented dashboards.

## Responsibilities

- Supported extraction and integration of website and campaign data.
- Assessed field completeness, consistency, and suitability for reporting.
- Structured data in PostgreSQL for analysis and dashboard consumption.
- Developed and refined SQL queries for marketing and acquisition metrics.
- Designed Metabase views for recurring stakeholder questions.
- Documented metric definitions, assumptions, and known limitations.

## Technology

| Layer | Technology |
|---|---|
| Source analytics | Google Analytics 4 |
| Data movement | Airbyte |
| Storage and querying | PostgreSQL, SQL |
| Development environment | DataGrip |
| Business intelligence | Metabase |

## Analytical Focus

The dashboard work addressed questions such as:

- How did traffic change over time?
- Which channels and campaigns contributed to acquisition?
- How did users move through key website interactions?
- Which metrics required additional qualification because of attribution, tracking, or data-quality limitations?

## Data-Quality Considerations

Website analytics are affected by tracking implementation, consent settings, attribution rules, bot traffic, campaign-tag consistency, and changes to site structure. Dashboard metrics were therefore treated as decision-support indicators rather than perfect measurements of user behaviour.

## Outcome

The project delivered a more accessible reporting layer for website and campaign analysis, reducing reliance on GA4’s default interface and helping stakeholders review marketing performance through consistent dashboard views.

## Public-Safe Supporting Material

The following artifacts may be added later if they can be created without exposing confidential information:

- a generalized pipeline diagram;
- a KPI dictionary using generic field names;
- a dashboard mock-up built with synthetic data;
- representative SQL patterns based on a fictional schema.

