
# Semarchy Franchise Web App Planning

## Phase 1 — Customer & Shop Registry
- Entities: Customer, ShopLocation, Franchisee, CustomerVisit.
- UI Components: Business Views, Collection Views, Forms, Display Cards.
- Display Cards use SemQL expressions for primary, secondary, and supporting text.

## Phase 2 — Data Ingestion & Quality
- NamedQuery endpoints and ModelJobs for decentralized ingestion.
- DupsManager for deduplication.
- SemQL-based validation rules.

## Phase 3 — Governance & Security
- ModelPrivGrant for scoped franchise access.
- Enhanced search forms, steppers, conditional formatting.

## Data Model Summary
- Customer: name, contacts, blood group, preferred shop, address.
- ShopLocation: shop info, geo-coordinates, address, franchisee reference.
- Franchisee: owner info.
- CustomerVisit: visit logs.

## UI Features for Website
- Navigation via Business Views.
- Collections for browsing.
- Forms and Steppers for authoring.
- Display Cards with images and SemQL expressions.

## GitHub Copilot Prompt (included in plan)
- Instructions to generate SEML objects (entities, LOVs, display cards, navigation).
- Ensures valid SEML headers and expressions.

