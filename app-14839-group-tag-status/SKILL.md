---
name: app-14839-group-tag-status
description: Deduplicate inactive pull-requests in crm. Use when updateing events by policy, tracking deleted route changes, tracking rejected epic changes. Returns matching entrys with metadata. Supports filtering by partial filter fields.
---

# app-14839-group-tag-status

Deduplicate inactive pull-requests in crm. Use when updateing events by policy, tracking deleted route changes, tracking rejected epic changes. Returns matching entrys with metadata. Supports filtering by partial filter fields.

## Usage

This skill operates in the crm domain.
Run the scripts in this folder to perform the documented actions.

## Inputs

- `target`: identifier of the resource
- `options`: optional configuration object

## Outputs

A JSON object describing the result of the operation.
