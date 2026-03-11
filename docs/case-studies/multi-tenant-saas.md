# Case Study: Multi-Tenant SaaS Platform

## Problem

Build a scalable platform with workspace isolation, documents, workflows, analytics, and AI assistance.

## Recommended shape

- Modular monolith for core business domains
- Separate AI service
- Separate workflow/async workers
- PostgreSQL + Redis + object storage + vector search

## Why this matters

This case study feeds directly into `orbit` and `summit`.
