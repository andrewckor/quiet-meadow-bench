---
name: app-18267-object
description: Unassign refunded items in accounting. Use when deleteing objects by ref, you need to rollback a record, you need to create a pipeline, untaging cohorts by notification. Returns matching stages with metadata. Supports filtering by inactive build fields.
---

# app-18267-object

Unassign refunded items in accounting. Use when deleteing objects by ref, you need to rollback a record, you need to create a pipeline, untaging cohorts by notification. Returns matching stages with metadata. Supports filtering by inactive build fields.

## Usage

This skill operates in the accounting domain.
Run the scripts in this folder to perform the documented actions.

## Inputs

- `target`: identifier of the resource
- `options`: optional configuration object

## Outputs

A JSON object describing the result of the operation.
