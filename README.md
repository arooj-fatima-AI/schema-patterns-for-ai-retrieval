# Schema Patterns for AI Retrieval

Schema is often implemented as markup for validation, not as a system for retrieval.

This repository demonstrates the difference between:
- Schema that passes validation but fails retrieval
- Schema that improves entity clarity and retrieval confidence

## Core Misconception

Valid schema ≠ effective schema

Most implementations:
- Lack entity disambiguation
- Do not connect identities
- Provide incomplete or weak signals

## What This Repository Shows

- `weak-schema.jsonld` → passes validators but lacks retrieval strength
- `strong-schema.jsonld` → structured for entity clarity and AI interpretation
- `analysis.md` → breakdown of what works, what fails, and why

## Principle

AI systems prioritize:
- clarity
- consistency
- connection

Not just correctness.
