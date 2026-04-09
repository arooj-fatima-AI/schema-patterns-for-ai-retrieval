# Schema Analysis: What Works vs What Fails

## Weak Schema Problems

- No @id → entity is not uniquely identifiable
- No sameAs → no cross-platform identity validation
- No relationships → isolated entity
- Generic job title → low semantic clarity

Result:
- Passes validation
- Fails retrieval confidence

---

## Strong Schema Advantages

- Uses @graph → connects entities
- Includes @id → enables entity persistence
- sameAs → reinforces identity across platforms
- Entity relationships → builds context

Result:
- Higher retrieval confidence
- Stronger entity disambiguation
- Better AI interpretation

---

## Key Insight

Schema is not about:
- passing tools
- adding markup

Schema is about:
- defining identity
- reducing ambiguity
- guiding retrieval systems

---

## Critical Distinction

Validators check syntax.

AI systems evaluate:
- structure
- consistency
- authority signals
